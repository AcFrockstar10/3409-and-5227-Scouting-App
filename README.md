# FTC BIOBUZZ Scouting & Strategy App (2026–2027 Season)

A lightweight, offline-first web scouting application built for the **2026–2027 FIRST Tech Challenge season (BIOBUZZ)**. Designed for tablets, laptops, and phones at competitions with zero build step required.

## Features

- **Live BIOBUZZ Scoring Engine**:
  - **Autonomous**: Robot Leave (`+3`), Auto Park (`+5`), Auto Hive Tips (`+20`), Auto Hive Elements (`+2`).
  - **TeleOp & Endgame**: TeleOp Hive Tips (`+20`), Hive Cell Elements (`+2`), Bottom Nectar Bonus (`+5`), Owned Flower Elements (`+2`), Garden Elements (`+1`), Endgame Park (`+5`).
  - **Penalties**: Tracks Minor (`+5`) and Major (`+20`) fouls committed.
- **Ranking Point (RP) Telemetry**:
  - Live indicators for **Swarm RP** (16+ pts), **Pollinator 1 RP** (4+ Hive Tips), and **Pollinator 2 RP** (7+ Hive Tips).
- **Team Analytics Leaderboard**:
  - Aggregates average match score, Auto average, TeleOp average, average Hive Tips, Swarm RP hit rate, and foul averages per team.
- **Offline Persistence & Multi-Tablet Sync**:
  - Stores data locally in `localStorage`.
  - **Export CSV** for Google Sheets / Excel analysis.
  - **Export / Merge JSON** to combine match logs across multiple scouting tablets without duplicates.

## Quick Start

1. Open `index.html` directly in any web browser, or host this repository on **GitHub Pages**, **Netlify**, or **Vercel**.
2. Use the **Clear Sample Data** button under **Match History** before starting official tournament scouting.

## Repository Structure

```text
ftc-biobuzz-scout/
├── index.html          # Complete single-file scouting application
├── README.md           # Documentation and setup instructions
├── .gitignore          # Standard Git ignore rules
└── package.json        # Optional static dev-server configuration
```
