<div align="center">
  <!-- LOGO -->
  <img src="cropped_circle_image.png" width="150" alt="YAPORA Logo">
  
  <h1>🐱 YAPORA</h1>
  <p><b>Talk Freely. Share the Moment.</b></p>

  <!-- BADGES -->
  <img src="https://img.shields.io/badge/Platform-Android-green.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Kotlin-purple.svg" alt="Kotlin">
  <img src="https://img.shields.io/badge/UI-Jetpack_Compose-blue.svg" alt="Compose">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
  <a href="https://streamvault-eta-sable.vercel.app/">
    <img src="https://img.shields.io/badge/Website-Live-brightgreen.svg" alt="Website">
  </a>
</div>

---

YAPORA is a public Android chat app built with Kotlin and Jetpack Compose. Guests can send text messages and memes in one shared Firebase Realtime Database room.

🌐 **Official Website:** [https://streamvault-eta-sable.vercel.app/](https://streamvault-eta-sable.vercel.app/)

## ✨ Features
- **Anonymous Sign-in:** Secure guest login via Firebase Authentication.
- **Public Chat:** Real-time messaging backed by Firebase Realtime Database.
- **Rich Content:** Send text messages (up to 500 chars) or pick from 16 built-in memes.
- **Ephemeral Messages:** Messages automatically expire after one hour (cleaned up by a Cloud Function).
- **In-App Updates:** Seamless update flow via GitHub Releases with integrity checks, forced update options, and APK hash verification.
- **Premium UI:** Dark purple Material 3 interface with custom cat/chat branding.

## 🚀 Getting Started

### Prerequisites
- Android Studio with JDK 17
- Android SDK 35 (Android 6.0 / API 23+)
- A configured Firebase Project (Auth & Realtime Database)
- Node.js 22 (for deploying Cloud Functions)

### 📦 Build Instructions
Clone the repository and build the debug APK on Windows:

```powershell
.\gradlew.bat :app:assembleDebug
