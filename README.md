# ADV Mission Control & Tactical HUD 🏍️💨

A dual-purpose tactical suite designed for Adventure Motorcycling. This repository contains two independent Progressive Web Apps (PWAs) built for mission planning and real-time handlebar telemetry.

---

## 🛰️ 1. ADV Mission Control (v2.0)
**The Ultimate GPX & Roadbook Planner.**
Designed for desktop planning and mobile field-reference.

### [🚀 Launch Mission Control](https://wackywaynesa-blip.github.io/adv-mission-control/)

### Key Features:
*   **Tactical Map Engine:** Toggle between High-Contrast Dark and Satellite Recon layers.
*   **Smart Roadbook:** Automated arrival time calculation based on KPH, fuel range, and meal stops (🍟 🍔 ⛽).
*   **Predictive Weather Scan:** Real-time weather data for every stop specifically at your calculated arrival time.
*   **Elevation HUD:** Dynamic elevation profiles via GPX data or Open-Meteo API scan.
*   **Print-Ready Export:** Generates a 60mm wide roll-chart style roadbook for handlebar mounting.
*   **Mission Save/Load:** Export your entire plan as a JSON file for future deployment.

---

## ⚡ 2. ADV Tactical HUD
**Real-Time Handlebar Dashboard.**
Optimized for mobile browsers and mounted use on the bike.

### [🏁 Launch Tactical HUD](https://wackywaynesa-blip.github.io/adv-mission-control/ANDROID/hud.html)

### Key Features:
*   **Massive Speedometer:** High-visibility GPS-based ground speed (KM/H).
*   **Lean Angle Meter:** Real-time roll tracking with "Peak Lean" memory.
*   **G-Meter:** Visual ball-in-tube accelerometer to track braking and acceleration forces.
*   **Tactical Compass:** Digital heading tape with cardinal directions.
*   **Battery & USB HUD:** Monitor phone charge and charging status from your bike's power port.
*   **Screen Wake Lock:** Built-in toggle to keep your screen active throughout the ride.

---

## 📲 How to Install as an App (PWA)

Both tools are **Progressive Web Apps**, meaning they can be installed directly onto your phone without an app store:

1.  Open the link in **Chrome** (Android) or **Safari** (iOS).
2.  Tap the **Menu** (three dots) or **Share** icon.
3.  Select **"Add to Home Screen"**.
4.  Launch from your home screen for a full-screen, standalone experience.

---

## 🛠️ Technical Specs
*   **Mapping:** Leaflet.js
*   **Weather/Elevation:** Open-Meteo API
*   **Telemetry:** Browser Geolocation & DeviceOrientation APIs
*   **Offline Support:** Service Workers & Web Manifests

*Built for the ADV Community by wackywaynesa-blip.*
