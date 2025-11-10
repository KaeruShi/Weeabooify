<div align="center">

# 🌸 Weeabooify
### Beautiful & Aesthetic Theme Engine for Android

[![Platform](https://img.shields.io/badge/Android-12%2B-green?style=for-the-badge&logo=android)]()
[![Sold](https://img.shields.io/badge/Sold-800%2B-orange?style=for-the-badge&logo=shopping-cart&logoColor=white)]()
[![Telegram](https://img.shields.io/badge/Telegram-Join-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/weeabooify)
[![PayPal](https://img.shields.io/badge/Donate-PayPal-0070ba?style=for-the-badge&logo=paypal)](https://paypal.me/kaerushi)


Weeabooify is a powerful theme engine that allows you to easily customize your Android user interface — including QS panel, lockscreen, icons, and more — with a beautiful and aesthetic touch.

<img src="assets/resources/preview.png" alt="Preview" width="95%"/>

</div>

## ✨ Features
- Customize QS panel  
- Custom lockscreen interface  
- Icon packs, QS tile shapes, and notification backgrounds  
- SystemUI tweaks  
- And many more...  
> [!Note]
> You can check all features [here](FEATURES-AE.md)


## 🧰 Requirements
- Android 12 - 16 Beta (AOSP-based ROMs only).  
- [Magisk](https://github.com/topjohnwu/Magisk) / [KernelSU](https://github.com/tiann/KernelSU) / [SukiSU](https://github.com/SukiSU-Ultra/SukiSU-Ultra) / [Apatch](https://github.com/bmax121/APatch).  
- [LSPosed](https://github.com/JingMatrix/LSPosed) *(optionally with [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext/releases/latest) if required).*  
- Custom recovery with decryption support *(recommended as a fallback in case of bootloop).*
> [!IMPORTANT]
> On Android 16, only **lockscreen customization, icon pack, and notification background** features are supported.  
> Due to recent framework changes, QS Header styles and QS Tile Shapes are temporarily unavailable.

## 🛠️ Installation
1. Install the **Weeabooify** app.  
2. Open **LSPosed** and reoptimize **Weeabooify**.  
3. Enable **Weeabooify** and Select **SystemUI** and **Framework**.  
5. Open **Weeabooify**, grant all permissions, then log in to your account.  
6. Wait for the installation to finish → reboot your device → enjoy 🎉  

> [!Note]  
> For KernelSU users: root access must be manually enabled via the **KernelSU** app.

## ⚙️ How It Works
Weeabooify works by dynamically hooking and modifying Android’s SystemUI and Framework components at runtime — powered by the LSPosed engine.
This allows seamless theming and interface customization without modifying system files or flashing heavy overlays.

## 🖼️ Preview
For a detailed look at the **Weeabooify** app interface and features, please visit the [Preview Gallery](PREVIEW.md).  
The gallery provides a comprehensive set of screenshots highlighting the app’s design, customization options, and user experience.

## ❤️ Credits
Special thanks to:
- [Android Open Source Project (AOSP)](https://source.android.com) — Android source code  
- [Substratum](https://github.com/substratum/substratum) — Overlay engine references  
- [@DrDisagree](https://github.com/Mahmud0808) — Backend implementation support  

## ⬇️ Download
Weeabooify is available for a **one-time purchase of $5**.  
Support development and unlock all features via the following platforms:

- [Ko-Fi](https://ko-fi.com/s/52b3fa4d26)  
- [PayPal](https://paypal.me/kaerushi)  
- e-Wallet & Bank transfer *(contact [@KaeruShi](https://t.me/kaerushi))*  

## 🤔 FAQ

<details>
<summary>📱 Is my device supported?</summary>

- Weeabooify supports **Pixel devices** and **AOSP-based custom ROMs**.
- Not supported: OEM ROMs such as MIUI, OneUI, OxygenOS, ColorOS, iOS, etc.  
</details>

<details>
<summary>🔨 How to fix bootloop/BSOD?</summary>

- Boot into **Safe Mode** or  
- Delete the Weeabooify module from `data/adb/modules/` via custom recovery.  
</details>

<details>
<summary>🌐 What is AE?</summary>

- **AE (Anti-Entropy)** is one of the Weeabooify variants.  
- Two available variants:  
  - **Anti-Entropy** → for Android 12+  
  - **Schicksal** → for Android 10 (Substratum)  
- Each variant is sold separately.  
</details>

<details>
<summary>💵 I already paid, what should I do next?</summary>

- Contact me on Telegram: [t.me/kaerushi](https://t.me/kaerushi)  
- Send your **payment screenshot** as proof  
- You will then receive installation access/instructions  
</details>
