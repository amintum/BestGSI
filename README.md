<img width="500" height="160" alt="image" src="https://github.com/user-attachments/assets/21aff85d-df2c-4b6b-a1e5-5daa595e76c8" />

![Android Version](https://img.shields.io/badge/Android-16-3DDC84?style=for-the-badge&logo=android)
![Architecture](https://img.shields.io/badge/Architecture-arm64--ab-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable-success?style=for-the-badge)

BestGSI has Zero Bloat, giving users freedom to use what they want.

This project is based on **RestlessOS** by Christopher A. Williamson [`cawilliamson`](https://github.com/cawilliamson/treble_restlessos), which itself is a fork of **GrapheneOS** packaged as a GSI. BestGSI takes that secure, privacy-respecting foundation and strips it down to the absolute bare essentials, giving you complete control over your device.

 > Scroll Down for ScreenShots

---

## ⚡ BestGSI — Key Features

## ✨ Highlights & System Experience

* **Zero Bloatware:** We believe in user choice. BestGSI comes with a strictly minimal app drawer. There are no unwanted system tools or forced services. The only extra is **TuffBrowser**, a tiny, privacy-focused browser, so you can get started right away. You get a clean slate to install exactly what *you* want.
* **Pre-installed TuffBrowser:** Minimal, ultra-fast modern web browser under 2 MB with a built-in download manager.
  ↳ *[Open-Sourced Repo](https://github.com/amintum/Tuff-Browser)*
* **Custom Default Wallpaper:** Unlike upstream RestlessOS, which boots to a pitch-black background, BestGSI ships with a beautiful, pre-configured default wallpaper for a better first-boot experience.
* **New Bootanimation:** Sleek, high-frame-rate startup animation replacing the legacy boot animation.

## GrapheneOS DURESS PIN Feature

**Setting this PIN and entering it instead of your actual lock screen PIN during an unexpected or coercive situation destroys the device data and keeps you safe.**

---

##  Quick Settings & Audio Controls
**A newly Redesigned QS Panel ditching the AOSP panel design**
* **Side-by-Side Brightness & Volume Sliders:** Brightness and Volume sliders sit next to each other for effortless one-handed control and rapid adjustments.
* **Integrated 3-State Volume Switcher:** Tap the ringer icon inside the volume slider to cycle between **Sound (Ring)**, **Vibrate**, and **Silent** without reaching for the hardware volume rocker.
* **Mobile Data Tile:** Tap to turn mobile data ON/OFF straight from the Quick Settings shade. **Double-tap** to switch the active data SIM between **SIM 1** and **SIM 2** on dual-SIM devices, with no need to dive into system network settings.
  ↳ *[Open-Sourced Repo](https://github.com/amintum/MobileDataTile)*
* **Transparent QS Panel:** Sleek, translucent glass/blur effect across the Quick Settings and notification shade, with a dedicated switch in **BestGSISettings** to change between transparent and solid background anytime.
* **Cleaner UI:** Removed the drag/pill handle from the notification panel and launcher for a minimal, unobstructed view.
* **100% Brightness on Boot:** Maximum display clarity right upon startup.
* **Default Dark Mode on Boot:** Ships with Dark Theme enabled out of the box.
  ↳ *[Open-Sourced Repo](https://github.com/amintum/DarkModeOverlay)*
* **Clean Status Shade:** Suppressed the persistent USB Debugging notification.

---

##  Launcher, Widgets & Home Screen

* **Live Cyber Clock HUD Widget:**
  ↳ *[Open-Sourced Repo](https://github.com/amintum/CyberClockHudWidget)*
  * Pre-placed by default across the top row of the Home Screen on first boot.
  * **Zero-Latency Hardware Clock:** Powered by native hardware `TextClock` RemoteViews for live seconds and full calendar date tracking with zero battery drain.
  * **3-Column Live Telemetry:** Real-time **Battery % + Charging Indicator**, **RAM %**, and **Storage %** with refined **3.8dp** glowing Cyber Cyan progress bars.
  * **Tight Ribbon Profile:** Fits cleanly across 4-column and 5-column grids with zero wasted touch space.
* **Redesigned Lock Screen Clock:** Streamlined and modernized lock screen clock typography.
* **Custom Launcher3 QuickStep:**
  ↳ *[Open-Sourced Repo](https://github.com/amintum/Launcher3QuickStep)*
  * **Transparent App Drawer & Recents:** Translucent glass background for the app drawer and recent apps overview. Bring back a solid app drawer background anytime: hold touch on the home screen → **Home Settings** → toggle **Solid app drawer background**.
  * **Clone Apps (Dual Apps):** Run multiple accounts at once for social media, messaging, and gaming apps. Hold any app icon and select **Clone app** to create an isolated secondary profile instance.
  * **Share Installed Apps:** Hold any app icon and tap **Share** to send the raw `.apk` file directly through Android's native share sheet.
  * **Easy App Uninstallation:** Hold any app icon for an immediate **Uninstall** shortcut.
  * **Search Bar Polish:** Updated app drawer search bar outline styling and smooth dynamic icon animations.
  * **Pill Bar Removed:** Eliminated the top pill indicator bar above the launcher search bar.

---

##  System, Privacy & Freedom

* **Complete `FLAG_SECURE` Bypass:(Anti-DRM)**
  * Removed screenshot, screen recording, casting, and mirroring restrictions across the entire operating system.
  * Capture screenshots and screen recordings inside banking apps, Telegram secret chats, and DRM-protected streaming media without black screens.
* **Universal App Downgrade Support:**
  * Package downgrade protection bypassed at the framework level. Install older APK versions directly over newer installed versions without uninstalling or losing app data.
* **Legacy App Warning Suppressed:**
  * Completely eliminated the *"This app was built for an older version of Android"* popup when launching older or classic apps.

---

##  BestGSI Exclusive Settings
*(Prominently featured at the top of the main Android Settings page)*

* **Freeform & Multi-Window:** 1-tap toggles to enable desktop-style freeform floating windows and resizable split-screen multitasking.
* **Fast Animations Toggle:** Boost UI responsiveness with pre-tuned fast window and transition animation presets.
* **QS Panel Background Switch:** Switch between a transparent and a solid Quick Settings panel anytime.
* **Real-Time Network Speed Meter:** Live status bar upstream/downstream transfer speed indicator with dynamic units (KB/s & MB/s).
* **Font Engine (30+ Integrated Fonts):** Live font previews and system-wide font switching *(limited functionality depending on vendor overlay support)*.
* **Status Bar Clock Seconds & Battery % Toggles:** Customize status bar clock seconds and fine-tune the battery percentage display format.
* **In-App Browser & Community Hub:** Built-in manifesto, fast in-app web browser, direct Telegram/GitHub community links, and QR support.
* **Clean System Status View:** Real-time hardware telemetry dashboard showing RAM usage, storage capacity, kernel version, and SELinux status.

---

##  Gestures & Hardware Device Support

* **Universal Double Tap to Sleep (DT2S):** Supported across all devices on both the status bar and lockscreen.
* **Double Tap to Wake (DT2W) for Transsion Devices:**
  * Native support for Infinix & Tecno devices.
  * **Path to enable:** `Settings` → `System` → `TrebleDroid Settings` → `Transsion Settings` → `Enable DT2W`

---

##  Variants & Choosing a Build

* **GAppStore:** Ships with GrapheneOS App Store with GmsCompat, which lets you download and run Google Play Store & Services in a sandboxed environment.
* **Vanilla**
* **MicroG (beta):** Open-source alternative to Google services.

Builds are provided per **VNDK version** (31 and above, 30, 29, 28). To find yours:

* Install [Treble Info](https://gitlab.com/api/v4/projects/30453147/packages/generic/apk/5.2.3/TrebleInfo-free.apk), or
* Run `adb shell getprop ro.vndk.version`

>  **Do not guess.** A wrong build will bootloop your phone.

First boot takes 3 to 4 minutes. This is normal.

---

## 🤝 Credits & Acknowledgments

*   **Christopher A. Williamson (`cawilliamson`):** For the incredible work on [RestlessOS](https://github.com/cawilliamson/treble_restlessos) and the Treble patching logic.
*   **GrapheneOS:** The upstream foundation for this privacy and security-focused OS.

---

## Looking for Source Code ? 

Let me be honest with you. There is no source code because even I haven't built this from source code,
I took the precompiled [RestlessOS](https://github.com/cawilliamson/treble_restlessos) and made changes
to it by editing the stuff (meaning smali code patching) inside it, You are free to audit the image files and code.
I do wherever possible make changes open-source as you can see.
I don't have financial resources required for server costs to build from source code.
In future, if I start building from source code, I will definitely upload it.

---

### Flashing Guide 

 [Read Here](https://github.com/amintum/BeginnerGuidetoFlashingGSI)

# 💬 Support & Community

Need help, want to report a bug, or just want to stay updated on the latest builds and patches? Join our official community!

**[Join Discord](https://discord.gg/k7qqcYate)**


## 📸 Screenshots

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/bootanimation1.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/bootanimation1.png" width="340" height="496" alt="BootAnimation 1" /></a><br/>
      <b>BootAnimation 1</b><br/>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/bootanimation2.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/bootanimation2.png" width="340" height="496" alt="BootAnimation 2" /></a><br/>
      <b>BootAnimation 2</b><br/>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/LockScreen.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/LockScreen.png" width="340" /></a><br/>
      <b>Refined Lock Screen</b><br/>
      <sub>Ambient clock, system indicators, and refreshed wallpaper layout</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/Launcher1.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/Launcher1.png" width="340" /></a><br/>
      <b>Homescreen & Wallpaper</b><br/>
      <sub>Clean edge-to-edge UI layout without drag pill bar and double-tap to sleep</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/Launcher4.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/Launcher4.png" width="340" /></a><br/>
      <b>App Context Menu (Shortcuts)</b><br/>
      <sub>Long-press shortcuts: Clone app (<code>userId 999</code>), 1-tap Share APK, and Uninstall</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/Launcher2.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/Launcher2.png" width="340" /></a><br/>
      <b>App Drawer & Fast Search</b><br/>
      <sub>Polished search bar styling with animated icon & solid drawer background support</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/Launcher3.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/Launcher3.png" width="340" /></a><br/>
      <b>Home Settings</b><br/>
      <sub>Dedicated toggle to switch between solid and translucent app drawer background</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/QSPanel1.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/QSPanel1.png" width="340" /></a><br/>
      <b>Dual Sliders & Ringer Switch</b><br/>
      <sub>Side-by-side brightness & volume sliders with 3-state ringer toggle</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/QSPanel2.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/QSPanel2.png" width="340" /></a><br/>
      <b>Translucent Glass QS Shade</b><br/>
      <sub>Frosted glass Quick Settings background with dynamic Monet wallpaper tint</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/QSPanel3.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/QSPanel3.png" width="340" /></a><br/>
      <b>Dedicated Quick Settings Tiles</b><br/>
      <sub>1-tap mobile data toggle, double-tap SIM switcher, and screenshot tile</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/ScreenshotTileWindow.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/ScreenshotTileWindow.png" width="340" /></a><br/>
      <b>Screenshot Tile Window Settings</b><br/>
      <sub>Tile configuration window for status bar collapse behavior</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/BestGSISettings1.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/BestGSISettings1.png" width="340" /></a><br/>
      <b>System Dashboard</b><br/>
      <sub>Device specifications, Anti-DRM, and SELinux status indicators</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/BestGSISettings2.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/BestGSISettings2.png" width="340" /></a><br/>
      <b>Custom ROM Switches & Toggles</b><br/>
      <sub>QS background toggle, 0.5x animations, and app downgrade permissions</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://github.com/amintum/BestGSI/blob/main/Screenshots/BestGSISettings3.png"><img src="https://raw.githubusercontent.com/amintum/BestGSI/main/Screenshots/BestGSISettings3.png" width="340" /></a><br/>
      <b>System Font Selector</b><br/>
      <sub>System font switcher featuring 10+ custom font styles</sub>
    </td>
  </tr>
</table>

---
