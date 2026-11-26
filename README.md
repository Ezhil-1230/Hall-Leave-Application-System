# Hall Leave Application System

A cross-platform **Flutter** mobile application built to digitize hostel student leave requests, multi-tier warden approvals, and offline-resilient record synchronization.

---

## Tech Stack

- **Framework & Language:** Flutter, Dart
- **Backend & Cloud Sync:** Firebase Cloud Firestore
- **Offline Storage:** SQLite (local caching)
- **Target Platform:** Android (`com.example.ezhil`, `minSdk 24`, `targetSdk 36`)

---

## Key Features

- Digital student leave application forms with reason and date selectors
- Real-time request management dashboard for hall tutors and wardens
- Multi-tier approval workflows with status tracking
- Firebase Cloud Firestore synchronization with local SQLite offline caching

---

## Download & Install (Android APK)

The compiled release APK is available in [`release/Hall-Leave-Application-System.apk`](release/Hall-Leave-Application-System.apk).

1. Download **`Hall-Leave-Application-System.apk`** onto your Android device (`Android 7.0+` / API 24+).
2. Enable **Install from unknown sources** for your browser or file manager if prompted.
3. Open the APK file and tap **Install**.

---

## Build Note

This repository preserves the compiled Flutter release package (`libflutter.so`, `libapp.so`, `flutter_assets`).
