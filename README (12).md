# 🛡️ Kavach — Personal Safety App

> *"Because every life deserves protection."*

[![Download APK](https://img.shields.io/badge/Download-APK%20Beta-e8335a?style=for-the-badge&logo=android)](https://github.com/DarshMegh/kavach-app/releases/download/v1.0/Kavach.apk)
[![Website](https://img.shields.io/badge/Website-Live-50369e?style=for-the-badge&logo=github)](https://darshmegh.github.io/kavach-app)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

## 📹 Demo Video

[▶️ Watch Demo](https://github.com/DarshMegh/kavach-app/blob/main/demo-kavach.mp4.mp4)

---

## 📱 What is Kavach?

Kavach is a personal safety app built for Android that responds to emergencies **even when you can't ask for help**. No internet required. No backend server. Everything runs on your device.

Shake your phone. Scream. Fall. — Kavach responds instantly.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📳 **Background Shake Detection** | Shake phone 3 times — fires SOS even when screen locked |
| 🎙️ **Scream Detection** | Detects screams above 80dB even when app is closed |
| 🤸 **Fall Detection** | Detects sudden falls via accelerometer |
| 📹 **Auto Video Recording** | Silently records front + back camera on alert |
| 📍 **Silent SMS with GPS** | Sends live location to all emergency contacts instantly |
| 📞 **Auto Sequential Calling** | Auto-dials contacts one by one until someone picks up |
| 📱 **Fake Call** | Escape uncomfortable situations with a realistic fake call |
| ⏱️ **10 Second Cancel Window** | Accidentally triggered? Cancel before it fires |

---

## 🔒 Privacy First

- ✅ Zero backend servers
- ✅ No account required
- ✅ No data collection
- ✅ Works fully offline
- ✅ Videos saved to your own Google Photos
- ✅ SMS goes directly phone-to-phone

---

## 🚀 Tech Stack

- **React Native** 0.76.5
- **Native Kotlin** modules (5 custom modules)
- **4 Android Foreground Services** (Shake / Scream / Fall / Video)
- **MediaRecorder API** for silent video recording
- **SmsManager API** for silent SMS
- Zero dependencies on external servers

---

## 📲 Download & Install

1. [⬇️ Download Kavach APK](https://github.com/DarshMegh/kavach-app/releases/download/v1.0/Kavach.apk)
2. On your Android phone: **Settings → Security → Install Unknown Apps → Allow**
3. Open the downloaded APK and install
4. Open Kavach → Add emergency contacts → Stay protected

> ⚠️ This is a beta build. Play Store release coming soon.

---

## 🗂️ Project Structure

```
SafeHerApp/
├── android/app/src/main/java/com/safeherapp/
│   ├── ShakeDetectionService.kt        # Background shake detection
│   ├── ScreamDetectionService.kt       # Background scream detection
│   ├── FallDetectionService.kt         # Fall detection algorithm
│   ├── VideoRecorderService.kt         # Silent video recording
│   ├── SmsModule.kt                    # Silent SMS via SmsManager
│   └── MainApplication.kt             # Registers all 5 native modules
├── src/
│   ├── context/AlertContext.js         # Central alert state management
│   ├── screens/
│   │   ├── HomeScreen.js
│   │   ├── ContactsScreen.js
│   │   ├── SettingsScreen.js
│   │   ├── HistoryScreen.js
│   │   └── FakeCallScreen.js
└── app.json
```

---

## 👨‍💻 Developer

**Megh Mangal** — Kavach Studios

- 📧 [megh.darshmangal@gmail.com](mailto:megh.darshmangal@gmail.com)
- 🌐 [kavach-app website](https://darshmegh.github.io/kavach-app)
- 💼 BPIT, AI & Data Science

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">Built with ❤️ in India 🇮🇳</p>
