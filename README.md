# 🛰️ ISS Mission Control: Real-Time 3D Tracker

![Status](https://img.shields.io/badge/Status-Live-success)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🔴 Live Demo
### [Click Here to Launch Mission Control 🚀](https://codeveda26.github.io/iss-live-tracking/)
*(Works on Mobile & Desktop)*

---

## 📖 About The Project
A cinematic, interactive 3D visualization of the International Space Station (ISS) orbiting Earth. This application tracks the station in real-time, calculates its distance from the user, and displays detailed crew information for **Expedition 74**.

Built with a **Mobile-First** design philosophy, featuring a Sci-Fi "Mission Control" aesthetic.

---

## 🌟 Key Features

### 🌍 **3D Visualization**
- **Interactive Globe:** Uses **Mapbox GL JS** to render a realistic 3D Earth with atmospheric fog and star fields.
- **Real-Time Tracking:** Updates the ISS position (Latitude/Longitude) every 2 seconds.
- **Dynamic Trajectory:** Visualizes the station's path in real-time.

### 📊 **Live Telemetry & Maths**
- **Distance Calculator:** Uses the **Haversine Formula** to calculate the exact distance (in km) between the User and the ISS.
- **Flight Data:** Displays live Altitude (~400km) and Velocity (~27,600 km/h).

### 👨‍🚀 **Crew Manifest (Expedition 74)**
- **Interactive Roster:** Dropdown menu to view profiles of current astronauts (Feb 2026 data).
- **Agency Badges:** Visual indicators for NASA, Roscosmos, and ESA astronauts.
- **Smart UI:** Mobile-optimized popup cards that don't obstruct the map view.

### 📱 **Mobile-First UX**
- **Thumb-Friendly Controls:** Navigation and menus placed at the bottom for easy one-handed use.
- **Fail-Safe Mode:** Implements an Emoji marker fallback system if 3D assets fail to load on low-bandwidth networks.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Mapping Engine:** [Mapbox GL JS](https://www.mapbox.com/)
- **Data APIs:**
  - `wheretheiss.at` (Position Telemetry)
  - `open-notify.org` (Crew Data Logic)

---

## 🚀 Getting Started (Run Locally)

### Prerequisites
You need a valid **Mapbox Access Token**. You can get one for free at [mapbox.com](https://mapbox.com/).
