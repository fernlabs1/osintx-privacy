# OSINT X
**Developer:** FernLabs  
**Version:** 0.1.0  
**Platform:** Android (min SDK 24)

---

## Overview
**OSINT X** is an open-source intelligence (OSINT) companion app for Android that aggregates posts from X (formerly Twitter) related to topics of your choosing.  
It performs lightweight source validation, applies visual risk indicators, and estimates confidence scores based on external data—all locally on-device.

---

## Features
- 🔍 Automatic or manual account discovery for any topic  
- ⚡ Real-time feed from X API (Bearer token authentication)  
- 🎯 Color-coded risk levels (Low / Medium / High / Severe)  
- 🧠 Confidence scoring with external-source validation  
- 💬 Flag + optional note per account  
- ↔️ Swipe gestures: open in X / delete / edit  
- 🔒 Local-only storage (no external servers)  
- 🌙 Material 3 Compose UI + dark theme  
- 🪪 Encrypted credential store for API keys  

---

## Privacy
OSINT X never sends your topics, risk data, or API keys anywhere except directly to the official X API.  
See the full privacy policy here:  
👉 [https://fernlabs1.github.io/osintx-privacy](https://fernlabs1.github.io/osintx-privacy)

---

## Building
1. Clone the repo and open in **Android Studio Giraffe (AGP 8.2+)**  
2. Ensure `minSdk = 24`, `targetSdk = 35`  
3. Build the **debug** variant:  
