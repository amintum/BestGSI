<img width="454" height="165" alt="image" src="https://github.com/user-attachments/assets/aadd70db-0b40-4ae9-a60d-e551f9dca7e0" />

![Android Version](https://img.shields.io/badge/Android-16-3DDC84?style=for-the-badge&logo=android)
![Architecture](https://img.shields.io/badge/Architecture-arm64--ab-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable-success?style=for-the-badge)

BestGSI has Zero Bloat, giving users freedom to use what they want

This project is based on **RestlessOS** by Christopher A. Williamson [`cawilliamson`](https://github.com/cawilliamson/restlessos), which itself is a fork of **GrapheneOS** packaged as a GSI. BestGSI-Core takes that secure, privacy-respecting foundation and strips it down to the absolute bare essentials, giving you complete control over your device.
 
# ⚡ BestGSI — Key Features

---

## ✨ Core Highlights & System Experience
*   **Zero Bloatware:** We believe in user choice. BestGSI comes with a strictly minimal app drawer. There are no pre-installed browser trackers, unwanted system tools, or forced services. You get a clean slate to download and install exactly what *you* want.
*   **Custom Default Wallpaper:** Unlike the upstream RestlessOS which boots to a pitch-black background, BestGSI-Core ships with a beautiful, pre-configured default wallpaper out of the box for a better first-boot experience.
*   **Default Dark Mode on Boot** 
*   **100% Brightness on Boot:** Clean, high-visibility display output right from first startup.
*   **Cleaner UI:** Removed the drag/pill bar from the notification panel and launcher for a truly unobstructed edge-to-edge view.
*   **Silent Developer Mode:** Completely removed the persistent *"USB Debugging Connected"* notification popup.

---

## 🎛️ Quick Settings & Audio Controls
*   **Dedicated Cyber HUD Volume Quick Settings Tile:**
    *   One-tap access to an interactive volume panel with a smoked obsidian glass backdrop and glowing Cyber Cyan accents.
    *   **Continuous 0%–100% Smooth Sliders:** Fluid, high-precision adjustment for Media, Ring & Notifications, Calls, and Alarm without chunky step intervals.
    *   **1-Tap Quick-Mute (`[🔇]`):** Instantly mute any audio stream to 0% and tap again to restore the previous volume level.
    *   **Sound Profile Chips:** Quick-switch buttons for `[ SOUND ]`, `[ VIBRATE ]`, and `[ SILENT ]`.
*   **New Data SIM Quick Switcher Tile:**
    *   Added a 1-tap **Data SIM Switcher Tile** for Dual-SIM devices to switch active mobile data between **SIM 1** and **SIM 2** in under 100ms directly from your status bar.
*   **Transparent QS Panel:** Sleek, modern translucent blur backdrop for the Quick Settings and notification shade.
*   **Curated 12-Tile Default Layout:**
    *   `Internet` • `Bluetooth` • `Volume` • `Dark Mode` • `Airplane` • `Flashlight` • `Hotspot` • `Screen Record` • `Auto-Rotate` • `Location` • `Font Scaling` • `Data SIM Switcher`

---

## 📱 Launcher, Widgets & Home Screen
*   **Live Cyber Clock HUD Widget:**
    *   Pre-placed by default across the top row of the Home Screen on first boot.
    *   **Zero-Latency Hardware Clock:** Powered by native hardware `TextClock` RemoteViews for live seconds and full calendar date tracking with zero battery drain.
    *   **3-Column Live Telemetry:** Real-time **Battery % + Charging Indicator**, **RAM %**, and **Storage %** with refined **3.8dp** glowing Cyber Cyan progress bars.
    *   **Tight Ribbon Profile:** Fits cleanly across 4-column and 5-column grids with zero wasted touch space.
*   **Redesigned Lock Screen Clock:** Streamlined and modernized lock screen clock typography.
*   **Transparent App Drawer & Recents:** Beautiful translucent glass aesthetic for the launcher app drawer, clean search bar, and recent apps task switcher.

---

## 🛡️ Core System, Privacy & Freedom
*   **Complete `FLAG_SECURE` Bypass:**
    *   Removed screenshot, screen recording, casting, and mirroring restrictions across the entire operating system.
    *   Capture screenshots and record video seamlessly inside banking apps, Telegram secret chats, and DRM-protected media without black screens.
*   **Universal App Downgrade Support:**
    *   Package downgrade protection bypassed at the framework level; install older APK versions directly over newer installed versions without uninstalling or losing application data.
*   **Legacy App Warning Suppressed:**
    *   Completely eliminated the annoying *"This app was built for an older version of Android"* warning popup when launching older or classic applications.

---

## ⚙️ BestGSI Exclusive Settings
*(Prominently featured at the top of the main Android Settings page)*

*   **Freeform & Multi-Window:** 1-tap toggles to enable desktop-style freeform floating windows and resizable split-screen multitasking.
*   **Fast Animations Toggle:** Boost UI responsiveness with pre-tuned fast window and transition animation presets.
*   **Real-Time Network Speed Meter:** Live status bar upstream/downstream data transfer speed indicator with dynamic units (KB/s & MB/s).
*   **Font Engine (30+ Integrated Fonts):** Live typography font previews and system-wide font switching *(Note: limited functionality depending on vendor overlay support)*.
*   **Status Bar Clock Seconds & Battery % Toggles:** Easily customize status bar clock seconds and fine-tune the battery percentage display format.
*   **In-App Browser & Community Hub:** Built-in manifesto, fast in-app web browser, direct Telegram/GitHub community links, and QR support.
*   **Clean System Status View:** Real-time hardware telemetry dashboard displaying RAM usage, Storage capacity, Kernel version, and SELinux status.

---

## 👆 Gestures & Hardware Device Support
*   **Universal Double Tap to Sleep (DT2S):** Supported across all devices on both the status bar and lockscreen.
*   **Double Tap to Wake (DT2W) for Transsion Devices:**
    *   **Path to enable:** `Settings` → `System` → `TrebleDroid Settings` → `Transsion Settings` → `Enable DT2W`.


## 📸 Screenshots

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/03c29b33-e939-4d96-b3e9-e196b76c77d2" width="250" /><br>
      <b>Lock Screen</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/400341af-9908-4d6b-a37a-dcb1d8c284b4" width="250" /><br>
      <b>Home Screen</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/2068d025-d84b-4c65-a6fd-2eff0450ae88" width="250" /><br>
      <b>Quick Settings</b>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c5783ca9-a6e1-42a4-8a0c-24159abe5aa1" width="250" /><br>
      <b>Notifications</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/631e41ec-6a71-49a0-8ba0-79375cff57ba" width="250" /><br>
      <b>App Drawer/Launcher</b>
    </td>
   <td align="center">
      <img src="https://github.com/user-attachments/assets/a683139c-c90c-4a7a-a85c-98669f84ed91" width="250" /><br>
      <b>Recents/Background Application Window</b>
  </tr>
</table>


<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1a22a538-830a-494d-a00a-799496159aec" width="250" /><br>
      <b>Settings</b>
    </td>
       </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/3dda259b-97fd-4193-b07c-285dfd9681c7" width="250" /><br>
      <b>BestGSI Exclusive Settings 1</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/8c87bdf8-788a-4e0f-ae6f-23e8f7afa3fd"" width="250" /><br>
      <b>BestGSI Exclusive Settings 2</b>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/505d7091-7710-446e-b44f-c2f3eaf8eaeb"" width="250" /><br>
      <b>System Information</b>
    </td>
  </tr>
</table>

---

## 🤝 Credits & Acknowledgments

*   **Christopher A. Williamson (`cawilliamson`):** For the incredible work on [RestlessOS](https://github.com/cawilliamson/restlessos) and the Treble patching logic.
*   **GrapheneOS:** The upstream foundation for this privacy and security-focused OS.

---

### Flashing Guide 

 [Read Here](https://github.com/amintum/BeginnerGuidetoFlashingGSI)

# 💬 Support & Community

Need help, want to report a bug, or just want to stay updated on the latest builds and patches? Join our official community!

**[Join Discord](https://discord.gg/Ndjj4WNh3)**

**[Join the Telegram Support Group](https://t.me/amintumgsi)**
