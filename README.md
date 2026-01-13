# TFT GM+ Analytics

This project is an advanced analytical pipeline for **Teamfight Tactics**, focused on **Grandmaster+ level games**.

## 🎯 Goals

- Analyze TFT meta evolution at high-elo (GM / Challenger)
- Identify:
  - Hidden OP champions
  - Fake strong picks
  - Champion–item conditional performance
- Build a structured database for:
  - Coaching
  - Meta analysis
  - Patch reviews
- Final visualization via BI tools (Power BI)

## 🧱 Technical Stack

- **Python** — data ingestion & processing
- **Riot Games API (TFT)** — official data source
- **PostgreSQL** — structured game-level database
- **Power BI** — analytics & dashboards

## 📊 Data Scope

- Ranked TFT games
- Population: **Grandmaster+**
- Region: **EUW**
- Granularity:
  - Game-level analytics
  - Champion, item, trait, and placement data

## 🔐 Data & Compliance

- Uses **only Riot Games official APIs**
- No scraping
- No real-time gameplay interaction
- Rate-limited and cached requests
- Data used strictly for analytical and educational purposes

## 🚧 Project Status

Currently under active development:
- API ingestion pipeline in progress
- Database schema being finalized
- Match-level parsing implementation ongoing

---

*This project is non-commercial and intended for educational, analytical, and coaching use.*
