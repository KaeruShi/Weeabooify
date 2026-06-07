# How It Works

Weeabooify is built on top of the **LSPosed / Xposed** framework and uses runtime hooking to modify Android's SystemUI, Settings and Framework processes.

## Architecture Overview

```
Weeabooify App (User Process)
        │
        │  Preferences via RemotePreferences (ContentProvider)
        ▼
  SystemUI Process
        │
        │  YukiHookAPI hooks
        ▼
  Hooked Classes
  ├── ShadeHeaderController   → QS header styles & images
  ├── KeyguardRootView        → Lockscreen overlays & widgets
  ├── NotificationPanelViewController → Panel behavior
  └── ... (more SystemUI targets)
```

## Key Technology

- **[YukiHookAPI](https://github.com/HighCapable/YukiHookAPI)** — An efficient Hook API and Xposed Module solution built in Kotlin
- **[KavaRef](https://github.com/HighCapable/KavaRef)** — A modernizing Java Reflection with Kotlin
- **[RemotePreferences](https://github.com/apsun/RemotePreferences)** — About
A drop-in solution for inter-app access to SharedPreferences

## Why No System Modifications?

Unlike Substratum or manual overlay methods, Weeabooify hooks into running processes at **Zygote fork time** via LSPosed. This means:

- No need to modify `/system` or flash overlays
- Changes are applied live on reboot
- Easy to remove — just disable the module and reboot

## Safe Mode

If Weeabooify causes a crash loop, LSPosed's built-in safe mode will automatically detect repeated crashes and disable the module before the system becomes unbootable. You can also manually recover via:

- Android's built-in Safe Mode (volume down at boot)
- Deleting `data/adb/modules/weeabooify/` via custom recovery
