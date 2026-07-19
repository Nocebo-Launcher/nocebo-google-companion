# Nocebo Google Companion

Nocebo Launcher supports integrating the Google Feed page directly into your desktop using the **Nocebo Google Companion** application.

Due to Android security restrictions, the Google Feed API is strictly limited to pre-installed system apps (like the default launcher that came with your phone). To bypass this for a third-party launcher, you must manually install this companion APK. It uses a special `debuggable` workaround to safely bridge the connection between Nocebo Launcher and the Google App.

Because of this necessary workaround, this companion app **cannot be published on the Google Play Store** and must be downloaded and installed manually.

---

## 🚀 How to Enable Google Feed in Nocebo Launcher

1. Download and install the latest **Nocebo Google Companion APK**.
2. Ensure you are using the latest version of **Nocebo Launcher**.
3. Open Nocebo Settings.
4. Navigate to **Settings > Home Screen > Google Feed** and toggle the page on.
5. Swipe right on your home screen to enjoy your Google Feed!

---

## 🔒 Security & Privacy

This companion app acts **exclusively as a bridge**. 
- It has **zero** internet permissions.
- It cannot access your network, storage, or personal data.
- It includes a strict IPC security lock that **only** allows Nocebo Launcher to connect to it. No other apps on your device can hijack this bridge.
