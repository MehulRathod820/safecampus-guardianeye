# 🚨 GuardianEye | SafeCampus

> **Hold once. Your people know where you are.**

GuardianEye is a real-time, zero-friction personal safety web application designed for students, campus residents, and individuals in transit. In an emergency, it bridges the gap between distress and instant communication without requiring heavy apps or backend servers.

---

## ✨ Key Features

* **🚨 3-Second Hold SOS:** Designed to prevent accidental triggers. Uses a circular progress ring, haptic/vibration feedback, and touch/mouse pointer events.
* **📍 Live Location & GPS Dashboard:** Fetches high-accuracy latitude, longitude, and accuracy radius using browser-native Geolocation APIs. Includes a built-in accuracy radar and maps integration.
* **💬 Instant WhatsApp Deep-Linking:** Automatically formats a pre-filled emergency message containing a direct Google Maps pin and timestamp, sending it instantly to your saved trusted contacts (`wa.me`).
* **📢 Web Audio API Loud Siren:** A piercing, attention-grabbing oscillator wail controlled purely via user interaction to draw immediate help in unsafe zones.
* **👥 Trusted Contacts Management:** Securely stores up to 3 emergency contacts and custom SOS message templates locally using browser `localStorage` (privacy-first, nothing leaves your device).
* **📝 Incident Reporting Tool:** Allows users to log civic or campus safety issues locally, generate a unique reference ID (e.g., `SC-2410-7F3A`), and share reports via WhatsApp or Email.
* **⚡ PWA & Offline Ready:** Lightweight structure optimized for mobile screens, responsive glassmorphism UI, and offline caching support.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (via CDN)
* **Styling & Design:** Custom Obsidian Dark theme (`#020617`), Deep Emerald glassmorphism (`#022c22`), Bricolage Grotesque & DM Sans typography, FontAwesome 6 icons.
* **Logic & APIs:** Vanilla JavaScript (ES6+), Geolocation API, Web Audio API, LocalStorage API, MediaRecorder API.

---

## 🚀 How to Run Locally

1. Clone or download this repository.
2. Open the project folder in **Visual Studio Code**.
3. Open `index_mehul.html` (or `index.html`).
4. Click on **"Open with Live Server"** at the bottom of VS Code to run it instantly in your browser at `http://127.0.0.1`.

---

## 🔒 Privacy & Architecture
GuardianEye operates on a **client-side architecture**. There is no external database or server tracking your movements; your location and contacts stay strictly inside your device's browser until *you* choose to dispatch an SOS.

---
*Built for rapid prototyping & real-world safety impact.*
