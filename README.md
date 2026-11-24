# SmartBaq — Smart Greenhouse Mobile App

**SmartBaq** (*"Smart Garden"* in Kazakh) helps suburban dacha families and small-scale greenhouse owners control their greenhouse remotely from any distance, automate watering and climate rules, visually track crop growth by comparing produce size against familiar fruits and berries, and receive a green-screen harvest notification when crops ripen.

## Project Overview
- **Direction (Track):** Remote Microclimate Monitoring & Irrigation Automation, Smart Crop Growth & Harvest Planning
- **Target User:** Working families managing a 20–50 m² polycarbonate greenhouse from a distance during the spring-to-autumn growing season (for example, dacha owners near Atyrau).
- **Planned Tech Stack:** Flutter + Firebase / Supabase
- **Own Extra Feature:** Visual Crop Size & Growth Comparison Tracker (comparing current crop size to familiar fruits and berries like a pea, cherry, walnut, or ripe produce) + Green-Screen "Ready to Harvest!" Notification upon full ripeness.

## Required Modules (M1–M8)
- **M1 — Login:** Email and password authentication via Firebase/Supabase Auth for authorized family members.
- **M2 — Dashboard:** Live display of air temperature (°C), air humidity (%), soil moisture (%), and light level (lux).
- **M3 — Control:** Remote ON/OFF toggles from any distance for drip irrigation pump, exhaust fan, shade curtain, and grow lights.
- **M4 — Automation:** User-configured `IF–THEN` threshold rules (e.g., *IF soil moisture is below 35%, THEN turn ON watering pump for 10 min*; *IF temp is above 32°C, THEN turn ON fan*).
- **M5 — Alerts:** Instant warning banners and alert history log when temperature, humidity, or soil moisture crosses critical limits.
- **M6 — History & Charts:** 24-hour and 7-day line charts tracking temperature, humidity, and soil moisture trends.
- **M7 — Settings:** Crop-specific min/max threshold configuration, °C/°F unit toggle, and master automation switch.
- **M8 — No-Internet Mode:** Local caching of latest readings/states with `"Offline — showing last synced data"` banner and queued commands.

## Team Members & Roles (3 Members)

| Team Member | GitHub Handle | Role | Responsibilities |
| :--- | :--- | :--- | :--- |
| **Shakhmetova Aktoty** | `@ashakhmet24` | **Team Lead & Backend/DB** | Project charter, Firebase/Supabase database setup, M4 automation rules, M5 critical alerts |
| **Yerbolatkyzy Kaussar** | `@yerbolatovnaaa` | **UI/UX Designer & Frontend** | Figma prototype, logo/colors/fonts, M1 login, M2 dashboard, M3 remote device control |
| **Igilik Korkem** | `@korkemm` | **Frontend, Extra Feature & QA** | M6 charts & history, M7 settings, M8 no-internet mode, Visual Fruit-Size Growth Comparison & green harvest screen, demo video |

## 6-Week Development Roadmap
- [x] **Week 1:** Project charter, GitHub repository setup, team roles
- [ ] **Week 2:** Clickable Figma prototype, logo/colors, system & data diagram
- [ ] **Week 3:** App navigation skeleton & live cloud database read connection
- [ ] **Week 4:** M1–M3 (Login, live dashboard, remote device control)
- [ ] **Week 5:** M4–M8 (Automation rules, alerts, charts, settings, offline mode)
- [ ] **Week 6:** Visual fruit-size comparison & green harvest notification, APK build, demo video & final defense
## Repository
(https://github.com/yerbolatovnaaa/SmartBaq_App.git)`
