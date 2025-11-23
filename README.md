# RV Apps

[![](https://img.shields.io/badge/Telegram%20(Owner)-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rjaakash)
[![CI Build](https://github.com/rjaakash/RV-Apps/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/rjaakash/RV-Apps/actions/workflows/ci.yml)
[![Stars](https://img.shields.io/github/stars/rjaakash/RV-Apps?style=for-the-badge)](https://github.com/rjaakash/RV-Apps/stargazers)
[![Downloads](https://img.shields.io/github/downloads/rjaakash/RV-Apps/total?style=for-the-badge)](https://github.com/rjaakash/RV-Apps/releases)
[![Latest Release](https://img.shields.io/github/release-date/rjaakash/RV-Apps?style=for-the-badge)](https://github.com/rjaakash/RV-Apps/releases/latest)

🚀 **Automated CI builds of RV Apps — optimized for both root and non-root users.**

---

## 📥 Download

**[Get the Latest Release Here](https://github.com/rjaakash/RV-Apps/releases/latest)**

---

## ✨ Features

* ⚡ **Fast & Clean:** Automated CI builds ensuring reliability.
* 🔄 **Always Up-to-Date:** Automatically updated with the latest patches.
* 🛠️ **Universal Support:** Works flawlessly on both **Root** and **Non-Root** devices.
* 📦 **Unique Package Name:** Installs alongside the official YouTube app (no conflict).
* 🛡️ **Root Protection:** Supports detaching to prevent Play Store updates.

---

## 📌 Requirements

### 📱 Non-Root Users
A MicroG implementation is required to sign in to your Google account. Install **one** of the following:

* **[ReVanced GmsCore (Recommended)](https://github.com/ReVanced/GmsCore/releases/latest)**
* [MicroG-RE](https://github.com/WSTxda/MicroG-RE/releases/latest)

### 🧩 Root Users
You need a rooted environment with **Zygisk** support.

1. **Root Manager:** You must have one of the following installed:
   * [Magisk](https://github.com/topjohnwu/Magisk) (Ensure Zygisk is enabled in settings)
   * [KernelSU](https://github.com/tiann/KernelSU)
   * [KernelSU Next](https://github.com/KernelSU-Next/KernelSU-Next)

2. **Zygisk Support (For KernelSU Users):**
   * Unlike Magisk, KernelSU does *not* have built-in Zygisk. You **must** install one of these modules:
     * [Zygisk Next](https://github.com/Dr-TSNG/ZygiskNext)
     * [ReZygisk](https://github.com/PerformanC/ReZygisk)

3. **Play Store Protection (Recommended):**
   * [zygisk-detach](https://github.com/j-hc/zygisk-detach) — Prevents the Play Store from overriding your modded app.

---

## 📦 Installation

### For Non-Root Users
1. **Keep Official App:** You do not need to uninstall the official YouTube or YT Music app.
2. **Install MicroG:** Download and install GmsCore from the requirements above.
3. **Install App:** Download the `RV-Apps` APK from the releases page and install it.
4. **Login:** Open the app and sign in.

### For Root Users (Magisk/KSU Module)
1. Ensure you have **Zygisk** active (Enable it in Magisk, or install Zygisk Next/ReZygisk for KSU).
2. Download the **Magisk Module (ZIP)** from the releases page.
3. Flash the ZIP file in your root manager (Magisk/KernelSU).
4. (Optional but Recommended) Flash **zygisk-detach** to block Play Store updates.
5. Reboot your device.

---

## ❓ FAQ

### General
**Q: How do I update the app?**
A: Simply download the new APK (Non-Root) or ZIP (Root) and install/flash it over the existing one. You do not need to uninstall the old version.

**Q: Why do non-root users need MicroG?**
A: Modded apps have a different package signature and cannot use the official Google Play Services for login. MicroG bridges this gap.

**Q: I can't log in / "Please check internet connection"?**
A: This is usually a MicroG issue. Ensure you are using the recommended **ReVanced GmsCore**. Also, try disabling "Battery Optimization" for GmsCore in your Android settings.

### Playback & Features
**Q: Videos are buffering or stopping after 1 minute?**
A: This is a known issue. Go to **Settings > ReVanced > Layout > Spoof client** and enable it (try selecting "iOS" or "Android VR").

**Q: Why are video segments skipping automatically?**
A: This is **SponsorBlock**. It automatically skips intros, outros, and sponsors. You can customize this behavior in **Settings > SponsorBlock**.

**Q: Can I remove YouTube Shorts?**
A: Yes. Go to **Settings > ReVanced > Shorts** and enable "Hide Shorts".

**Q: Why doesn't the Download button work?**
A: Native downloading is a server-side Premium feature. To download, you must use the "External Downloader" patch settings and link an app like NewPipe or YTDLnis.

### Root Specific
**Q: I am on KernelSU and the module isn't working?**
A: Ensure you have installed **Zygisk Next** or **ReZygisk**. KernelSU does not have built-in Zygisk support like Magisk does.

**Q: Why should root users use detaching?**
A: The Google Play Store often detects modded apps and tries to "update" them back to the official (unpatched) version. Detaching hides the app from the Play Store.
