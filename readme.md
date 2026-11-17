# 🎯 Meeda's 90-Day Protocol Command Center

![Protocol Status](https://img.shields.io/badge/Protocol-Day%201%20%2F%2090-rose?style=for-the-badge)
![Start Date](https://img.shields.io/badge/Launch%20Date-Nov%2017%2C%202026-sky?style=for-the-badge)
![Weight Target](https://img.shields.io/badge/Weight%20Goal-102.0%20kg%20%E2%86%92%2075.0%20kg-emerald?style=for-the-badge)
![Deployment](https://img.shields.io/badge/Hosted%20On-GitHub%20Pages-violet?style=for-the-badge)

An interactive, single-file executive habit-tracking and life-management command center built to synchronize daily time-blocked schedules, Google Drive workout programming, Arabic OMAD nutrition plans, Duolingo German language study, and smartwatch health telemetry over a structured **90-day transformation sprint**.

---

## 📋 Protocol Overview & Baseline Milestones

* **Launch Date:** Tuesday, November 17, 2026 (Protocol Day 1 of 90)
* **Body Composition Target:** `102.0 kg` $\rightarrow$ `75.0 kg` (`-27.0 kg` total transformation)
* **Cardiovascular Fat-Loss Zone:** `138 – 149 BPM` (Zone 2 continuous jogging + steady brisk walking)
* **Daily Freelance & BI Revenue Target:** `$30 – $50 / day` (Fiverr & Upwork deep-work delivery)
* **Language Milestone:** Daily 60-minute German progression (`A1` $\rightarrow$ `B1` via Duolingo + grammar drills)

---

## 🗓️ 3-Mode Weekly Operating Schedule

### 1. Weekday Protocol (`Sunday – Thursday`) — 10 Core Missions
| Time Window | Mission | Focus & Deliverable |
| :--- | :--- | :--- |
| **06:30 – 07:30** | **Mission 1: Morning Routine** | Personal hygiene, skin cream application, hydration, and morning coffee. |
| **07:30 – 11:30** | **Mission 2: Dev Plan 1** | Deep-work freelancing block (Fiverr & Upwork client delivery, `$30–$50` target). |
| **11:30 – 12:00** | **Mission 3: Commute to Gym** | Pre-workout hydration and mental transition. |
| **12:00 – 14:30** | **Mission 4: Gym Workout** | Custom daily routines synced from Google Drive (`Workoutplan` workbook). |
| **14:30 – 15:00** | **Mission 5: Commute Home** | Post-training recovery travel. |
| **15:00 – 17:30** | **Mission 6: Shower & OMAD** | Post-workout shower and single daily high-protein meal (`1200–1400 kcal`). |
| **17:30 – 18:30** | **Mission 7: Lucinda's Time** | Quality bonding with daughter Lucinda + evening commute preparation. |
| **18:30 – 19:30** | **Mission 8: German Study** | 25m Duolingo crowns + 20m verb/article drills (`der/die/das`) + 15m speaking. |
| **19:30 – 21:00** | **Mission 9: Jogging & Walk** | 30 min Zone 2 jogging (`138–149 BPM`) + 60 min steady brisk walking. |
| **21:00 – 23:30** | **Mission 10: Family & Study** | Evening family time, technical upskilling, and sleep wind-down. |

### 2. Friday Protocol (`British Council & Family Visits`)
* **05:30 – 09:30:** Commute to British Council in Cairo
* **09:30 – 11:30:** Dev Plan II (Academic & Professional Studying)
* **11:30 – 15:00:** Commute to Kafr El-Zayat
* **15:00 – 17:00:** Visiting Parents
* **17:00 – 18:00:** Visiting Parents-in-Law
* **18:00 – 22:00:** Friends Time

### 3. Saturday Protocol (`Glute Training & Padel Tennis`)
* **10:30 – 11:30:** Morning Routine
* **11:30 – 12:30:** Commute to Gym
* **12:30 – 14:30:** Gym Session (Glute Focus: Barbell Hip Thrusts, Sumo Squats, RDLs, Bulgarian Splits)
* **14:30 – 15:00:** Commute Home
* **15:00 – 17:00:** OMAD and Shower
* **17:00 – 17:30:** Commute to Club
* **17:30 – 19:30:** Playing Padel Tennis
* **19:30 – 23:00:** Family Time

---

## ✨ Key Dashboard Features

* **Zero-Backend Persistence (`localStorage`):** All daily task check-offs, workout movement logs, weight adjustments, and streak matrices save automatically in your browser with zero server setup required.
* **7-Day Master Controller (`Sun – Sat`):** Dynamically switches between Weekday, Friday, and Saturday schedules along with each day's exact gym exercises (start/end weights in `kg`, sets, and reps) and Arabic OMAD meal breakdown.
* **Wearable & Health Telemetry Bridge:** Supports live Web Bluetooth heart-rate pairing for smartwatches (`138–149 BPM` Zone 2 indicator), manual sliders/quick-nudge buttons, and CSV/JSON import from Samsung Health or Google Fit.
* **Interactive 10-Mission × 7-Day Consistency Matrix:** Real-time adherence bar chart and clickable weekly habit grid targeting an **85%+ daily completion threshold**.

---

## 🚀 How to Deploy Live on GitHub Pages

1. **Upload `index.html`:** Ensure the single-file dashboard (`index.html`) is placed in the root directory (`/`) of your GitHub repository.
2. **Open Repository Settings:** Navigate to **Settings** $\rightarrow$ **Pages** in your GitHub repository.
3. **Select Source Branch:** Under **Build and deployment**, set **Source** to **Deploy from a branch**, select `main` (or `master`), keep the folder set to `/ (root)`, and click **Save**.
4. **Access Your Live Command Center:** Within ~60 seconds, your live dashboard will be accessible at:
   ```text
   https://mohdkhallaf.github.io/Habit-Tracking/
   ```
5. **Mobile Home Screen Shortcut:** Open the GitHub Pages URL on your phone browser and tap **Add to Home Screen** to run it like a native app.

---

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5 (Single-File Architecture)
* **Styling:** Tailwind CSS (CDN) + Custom Dark Glassmorphism UI (`Plus Jakarta Sans`, `Inter`, `JetBrains Mono`, and `Cairo` for Arabic RTL nutrition cards)
* **Logic & Storage:** Vanilla JavaScript (ES6+), Web Bluetooth API, FileReader API (CSV/JSON), and Browser `localStorage`
