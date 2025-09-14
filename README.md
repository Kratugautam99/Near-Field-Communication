# 📡 Near-Field-Communication

Welcome to **Near-Field-Communication**, a dual-platform solution for interacting with NFC (Near Field Communication) tags and devices. This project combines the power of Web NFC and a native Android NFC reader app to offer seamless tag detection, reading, and writing capabilities.

---

## 🚀 Live Demo & Downloads

- 🌐 **Web NFC App**: [Launch Web NFC](https://web-nfc-ten.vercel.app) — interact with NFC tags directly from your browser *(Chrome for Android required)*  
- 📱 **Android NFC App**: [Download APK](./NFCApp.apk) — install the native NFC reader app for enhanced tag detection

---

## 📦 Project Structure

```bash
near-field-communication/
├── NFCReaderApp/         # Android NFC Reader App (Kotlin-based)
├── public/               # Static assets for Web NFC frontend
├── NFCApp.apk            # Prebuilt Android APK
├── .gitignore            # Git ignore rules
├── license.txt           # MIT License
├── package.json          # Node.js dependencies and scripts
├── server.js             # Express server for Web NFC
```

## 🧠 About the Project
This repository demonstrates two approaches to NFC interaction:

Web NFC: Uses the experimental Web NFC API to read/write NFC tags via supported browsers.

Android NFC App: A Kotlin-based mobile app built with Android Studio that supports reading and writing NDEF messages from physical NFC tags.

## 🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: Node.js, Express

Mobile: Kotlin, Android SDK

Deployment: Vercel (for Web NFC)

## 📚 Topics Covered
NFC tag detection and reading

Writing NDEF messages

RFID tag compatibility

Web NFC API integration

Android NFC development

## 📄 License
This project is licensed under the MIT License. See license.txt for details.

## 🙌 Contributing
Pull requests are welcome! If you’d like to improve the app, fix bugs, or expand functionality, feel free to fork the repo and submit a PR.

## ✨ Acknowledgments
Thanks to the pioneers of Web NFC and the open-source Android community for making NFC development accessible and exciting.
