# 🎵 Spotify Streams & Audio Features Analysis

A complete, single-workbook Excel analytics project exploring hit song characteristics, genre distributions, and multi-platform playlist curation across Spotify, Apple Music, Deezer, and YouTube.

---

## 📂 Repository Contents

* **`Spotify_Dataset_Project.xlsx`** – The complete project workbook containing cleaned data, pivot analyses, and the final interactive executive dashboard.
* **`Executive_Dashboard.pdf`** – A printable, high-resolution PDF export of the Executive Dashboard sheet.
* **`dashboard_preview.png`** – A quick screenshot preview of the Executive Dashboard.

---

## 📌 Project Architecture

Everything in the Excel workbook is organized into three core sheets:

1. **`Clean_Data`**: Standardized raw dataset featuring song metrics, engineered streaming performance categories (`1B+`, `500M–1B`, `250M–500M`, `Under 250M`), and platform playlist tallies.
2. **`Analytics_Pivots`**: Dynamic Pivot Tables cross-analyzing track audio attributes (Energy, Danceability, Valence, BPM) against stream tiers, top genres, and artist chart performance.
3. **`Executive_Dashboard`**: High-level summary dashboard with key metric KPIs (`Total Streams`, `Average Tempo`, `Billion-Stream Track Share`, `Unique Artists`) and multi-axis genre performance visuals.

---

## 💡 Key Analytical Findings

* **Audio Feature Trends**: Mega-hit songs (**1B+ streams**) favor higher **Danceability (66.5%)** with balanced Energy (65.8%). Across all streaming brackets, track tempo remains consistently around **118–120 BPM**.
* **Mass Reach vs. High Average Streams**: **Pop** dominates overall platform playlist presence (1.3M+ Apple playlists), while niche genres like **Soul** and **Alternative R&B** achieve the highest *average streams per song* (>1.6B average).
* **Cross-Platform Dominance**: Leading artists (e.g., Ed Sheeran at >16.5B streams) demonstrate strong, sustained chart rankings across Spotify, Apple Music, and Billboard.

---

## 🛠️ Excel Skills & Functions Used

* **Data Engineering**: Conditional bucketing using nested `IF`/`IFS` logic.
* **Formulas**: `SUM`, `AVERAGE`, `COUNTIF`, `COUNTA`, and `UNIQUE`.
* **Data Modeling**: Multi-table Pivot analysis and stacked reporting.
* **Dashboard Design**: Custom KPI scorecards and secondary-axis Combo Charts for executive reporting.
