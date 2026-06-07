# Troubleshooting

## Bootloop / BSOD after enabling

**Option 1 — Android Safe Mode**

Boot into Safe Mode (hold Volume Down during boot on most devices). This disables all third-party modules. You can then open LSPosed and disable Weeabooify.

**Option 2 — Custom Recovery**

Boot into your custom recovery and delete the module:

```
data/adb/modules/weeabooify/
```

This removes the module without needing to boot into Android.

## Module is enabled but nothing changes

- Make sure you selected **both SystemUI and Framework** in the LSPosed scope
- Try tapping **Reoptimize** in LSPosed for the Weeabooify entry
- Reboot after changing scope
::: warning ROM Issue
Your ROM may not be supported yet — report it to the support group with your ROM name and Android version
:::

## App shows "Trial Version" or features are locked

The PRO Version requires account login. Make sure you:

1. Have registered an account (email)
2. Are logged in inside the Weeabooify app
3. Have a stable internet connection for the first login
4. If still presist contact [@KaeruShi](https://t.me/kaerushi) for PRO activation


## Getting help

Join the [Telegram community](https://t.me/weeabooify) or contact [@KaeruShi](https://t.me/kaerushi) directly.