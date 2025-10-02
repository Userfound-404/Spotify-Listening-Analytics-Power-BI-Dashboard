# Spotify Listening Analytics — Power BI Dashboard

A Power BI dashboard that explores multi-year Spotify listening behavior, with interactive filters by platform and views for albums, artists, and tracks, including Latest Year vs Previous Year trends and Top 5 rankings.

---

## 📌 Overview
This repository contains a Power BI dashboard built from **personal Spotify listening history** to visualize what was played over time across platforms (Android, iOS, Mac, Windows, Web Player, Cast to device), along with summaries for albums, artists, and tracks.  
It highlights **year-over-year changes** and the **most-played items**.

---

## ✨ Key Features
- **Platform filter** to compare listening by Spotify app and device types (Android, iOS, Mac, Windows, Web Player, Cast to device).
- **Three dedicated views**: Albums, Artists, and Tracks, each showing “played over time” trends.
- **Latest Year (LY) vs Previous Year (PY)** KPI blocks with counts and percentage change.
- **Top 5 rankings** for Albums, Artists, and Tracks by total play counts.
- **Weekday vs Weekend** splits to reveal listening pattern differences.

---

## 🔍 Highlighted Insights
- **Scale of listening**:  
  ~7,907 albums, 4,112 artists, and 14K tracks played across the full timeline.

- **Albums**:  
  LY = 1,824 vs PY = 2,333 (**−21.82%**)  
  Totals include segments like 2,668 and 6,435 (63.08%).

- **Artists**:  
  LY = 1,071 vs PY = 1,455 (**−26.39%**)  
  Totals include 1,578 and 3,393 (63.15%).

- **Tracks**:  
  LY = 3,568 vs PY = 4,031 (**−11.49%**)  
  Totals include 5,106 and 11,714 (64.26%).

- **Top 5 Albums**:  
  The Beatles dominate with *Past Masters*, *Abbey Road*, *The Wall*, *Revolver* (counts ~1,038–1,429).

- **Top 5 Artists**:  
  The Beatles, The Killers, John Mayer, Bob Dylan, Paul McCartney (tallies ~2.7K–13.6K).

- **Top Tracks**:  
  Examples include *Ode To The Mets* (207), *In the Blood*, *Dying Breed* (166), *Caution*, *19 Dias y 500 Noches* (~148–181+).

---

## 📂 What’s Included
- **Dashboard PDF export**: `Spotify-analysis.pdf` for a quick visual tour of the report pages and KPIs.
- (Suggested) Add:
  - `.pbix` file for full interactivity
  - any data prep scripts or methodology docs

---

## 🚀 How to Use
1. Open the **PDF** to review KPIs, year trends, and Top 5 rankings.  
2. If the `.pbix` is available, open it in **Power BI Desktop**:
   - Use platform filters  
   - Switch between Albums / Artists / Tracks views  
   - Compare **LY vs PY**  
3. Apply the **Weekday/Weekend toggle** to analyze behavioral differences.

---

## 📊 Data Sources
- Personal Spotify **listening history export** (`StreamingHistory.json` / `.csv`),  
  aggregated to counts at album, artist, and track levels for time-series analysis.

---

## 📐 Metrics and Definitions
- **Albums/Artists/Tracks Played Over Time**: cumulative or period counts (2014–2024).  
- **LY vs PY**: most recent complete year vs immediately prior year, with absolute counts and % change.  
- **Top 5**: items ranked by total play counts in the selected context.  
- **Weekday vs Weekend**: split of plays by day-type.

---

## 📊 Example Figures
- Albums: **LY 1,824 vs PY 2,333 (−21.82%)**  
- Artists: **LY 1,071 vs PY 1,455 (−26.39%)**  
- Tracks: **LY 3,568 vs PY 4,031 (−11.49%)**  
- Top tracks include: *Ode To The Mets* (207), *Dying Breed* (166), *Caution*, *19 Dias y 500 Noches* (~148–181)
