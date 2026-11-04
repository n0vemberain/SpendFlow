# SpendFlow — Smart Personal Finance Tracker ৳

<p align="center">
  <img src="android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png" width="100" height="100" alt="SpendFlow Logo" style="border-radius: 24px; box-shadow: 0 10px 25px rgba(2, 132, 199, 0.35);" />
</p>

<p align="center">
  <b>SpendFlow</b> is a modern, lightweight, and offline personal income & expense tracker for Android, crafted with elegant iOS Frosted Glassmorphism aesthetics, intuitive bottom navigation, and zero clunky native controls.
</p>

<p align="center">
  <a href="https://github.com/n0vemberain/SpendFlow/releases/latest">
    <img src="https://img.shields.io/badge/Download-Latest%20APK%20(v1.0.0)-0284c7?style=for-the-badge&logo=android&logoColor=white" alt="Download APK" />
  </a>
</p>

---

## 📱 App Previews & Screenshots

<p align="center">
  <img src="screenshots/photo_1_2026-11-04_06-06-45.jpg" width="23%" alt="SpendFlow Screen 1" />
  &nbsp;&nbsp;
  <img src="screenshots/photo_2_2026-11-04_06-06-45.jpg" width="23%" alt="SpendFlow Screen 2" />
  &nbsp;&nbsp;
  <img src="screenshots/photo_3_2026-11-04_06-06-45.jpg" width="23%" alt="SpendFlow Screen 3" />
  &nbsp;&nbsp;
  <img src="screenshots/photo_4_2026-11-04_06-06-45.jpg" width="23%" alt="SpendFlow Screen 4" />
</p>

---

## ✨ Key Features

- **৳ Native Bangladeshi Taka Support**: Full support for Taka currency symbol natively formatted with commas (`৳ 45,000`).
- **iOS Frosted Glass Design**: Premium backdrop blur, soft glow ambient orbs, and rounded squircles.
- **Strict Color Separation**: 
  - **Income**: Pure vivid Emerald Green (`#16a34a`) for buttons, badges, and income toasts.
  - **Expense**: Proper vivid Red (`#dc2626`) for expense buttons, indicators, and alerts.
- **Fixed Bottom Navigation**: Pinned bottom bar (`Home` ➔ `Analytics` ➔ `History`) that stays locked to the bottom while scrolling.
- **No Native Cutoff Dropdowns**: All selects replaced with beautiful custom popover menus with smooth checkmarks.
- **Smart Date Management**: Automatically pre-fills today's local date on startup. Strictly prevents selecting future dates (`max=today`).
- **100% Offline & Private**: Zero external CDN calls or server dependencies; your financial data stays stored safely in local device storage.

---

## 📥 Installation

1. Download the latest APK from the [Releases](https://github.com/n0vemberain/SpendFlow/releases/latest) page or directly:
   - 👉 **[Download SpendFlow.apk](https://github.com/n0vemberain/SpendFlow/releases/download/v1.0.0/SpendFlow.apk)**
2. Open the downloaded `.apk` file on your Android device.
3. Allow *"Install from unknown sources"* if prompted by Android Settings.
4. Tap **Install** and enjoy managing your finances seamlessly!

---

## 🛠️ Tech Stack

- **UI / Frontend**: HTML5, Vanilla ES6+ JavaScript, Tailwind CSS (offline bundled).
- **Charts Engine**: Chart.js (offline bundled).
- **Mobile Framework**: [Capacitor](https://capacitorjs.com/) (Cross-platform native bridge).
- **Target OS**: Android (API 24+ / Android 7.0 through Android 15+).

---

## 📄 License

This project is licensed under the [ISC License](LICENSE).
