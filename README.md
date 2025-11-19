# RV Apps

<p align="center">
  <a href="https://t.me/rjaakash">
    <img src="https://img.shields.io/badge/Telegram%20(Owner)-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
  <a href="https://github.com/rjaakash/RV-Apps/actions/workflows/ci.yml">
    <img src="https://github.com/rjaakash/RV-Apps/actions/workflows/ci.yml/badge.svg?event=schedule" />
  </a>
  <a href="https://github.com/rjaakash/RV-Apps/stargazers">
    <img src="https://img.shields.io/github/stars/rjaakash/RV-Apps?style=for-the-badge" />
  </a>
  <a href="https://github.com/rjaakash/RV-Apps/releases">
    <img src="https://img.shields.io/github/downloads/rjaakash/RV-Apps/total?style=for-the-badge" />
  </a>
  <a href="https://github.com/rjaakash/RV-Apps/releases/latest">
    <img src="https://img.shields.io/github/release-date/rjaakash/RV-Apps?style=for-the-badge" />
  </a>
</p>

<p align="center">
  🚀 Automated CI builds of RV Apps — made for both root and non-root users.
</p>

---

## 📥 Download
**Latest Release:**  
https://github.com/rjaakash/RV-Apps/releases/latest

---

## ✨ Features
- ⚡ Fast, clean CI builds  
- 🔄 Automatically updated with every patch  
- 🛠️ Works flawlessly on root & non-root devices  
- 📦 Unique package name (safe for non-root devices)  
- 🛡️ Root users can stay Play Store–safe with detaching

---

## 📌 Requirements

### Non-Root Users
A microG implementation is required for login support:

- ReVanced GmsCore → https://github.com/ReVanced/GmsCore/releases/latest  
- MicroG-RE → https://github.com/WSTxda/MicroG-RE/releases/latest  

### Root Users
Magisk (with Zygisk enabled) is required.  
You must install the **Magisk module** provided in Releases.

Detaching is recommended to avoid Play Store interference:

- zygisk-detach → https://github.com/j-hc/zygisk-detach

---

## 📦 Installation

### 📱 Non-Root Installation
1. Your original YouTube / YouTube Music can remain installed — RV Apps uses a separate package name and installs alongside them.  
2. Install a microG implementation.  
3. Install the RV Apps APK from Releases.  
4. Sign in using microG.

---

### 🧩 Root Installation
1. Ensure Magisk is installed and Zygisk is enabled.  
2. Install the **Magisk module** (ZIP file) from the Releases section using the Magisk app.  
3. Install **zygisk-detach** to block Play Store detection and prevent forced updates.  
4. Reboot if required for the module to take effect.

---

## ❓ FAQ

**Why do non-root users need microG?**  
Modded apps cannot use official Google login without microG.

**Does RV Apps replace stock YouTube?**  
No. RV Apps installs as a separate app with its own package name.

**Why use detaching on root?**  
It stops the Play Store from updating or overriding the modded app.
