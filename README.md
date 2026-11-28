# 🏈 Gridiron Metrics

**Gridiron Metrics** is an interactive dual-league football analytics platform built with **Python** and **Streamlit**, delivering game-level telemetry, play-by-play situational scouting, and historical season recaps across both **College Football (CFB)** and the **NFL** (2004–2026).

* **Live Application:** [Gridiron Metrics on Streamlit Cloud](https://gridironmetrics.streamlit.app/)
* Note: Hosted on Streamlit Community Cloud—if asleep, click "Yes, get this app back up!" and allow ~30 seconds to wake 
---

## 🚀 Core Analytics Modules

### 1. 🔍 Single Game Box Score Inspector (CFB & NFL)
* **Hierarchical Drill-Down:** Filter seamlessly through **Conference / Division ➔ Team ➔ Schedule** across any regular-season or postseason matchup from **2004 to 2026**.
* **Official Team Box Score Telemetry:** Side-by-side comparison of Total Yards, Passing Yards, Rushing Yards, First Downs, Turnovers, 3rd Down Efficiency, and Completions/Attempts—with automated green statistical advantage highlighting.
* **Individual Statistical Leaders:** Identifies each team's top Passing, Rushing, and Receiving yardage performers paired with official roster position tags (`QB`, `RB`, `WR`, `TE`).
* **Timestamped Play-by-Play Log:** Chronological play log featuring running scoreboards, down-and-distance telemetry, situational success flags, explosive play indicators, and color-coded impact highlights (**Touchdowns**, **Field Goals**, and **Turnovers**).

### 2. 📊 Game Analysis Engine (CFB & NFL)
* Evaluates conference-wide and league-wide scoring profiles, average scoring margins, one-score game rates, and high-scoring shootouts (`60+` total points) across any selected season.

### 3. 🏟️ Down & Distance Play Scouting Engine (CFB & NFL)
* **Situational Slicing:** Filter play-by-play data by **Offensive Unit**, **Down Profile** (`1st` through `4th Down`), and **Impact Play Category** (All Plays, Impact Plays Only, Scoring Plays Only, Turnovers Only).
* **Film Room Metrics:** Computes **Situational Success Rate** (50% of distance on 1st down, 70% on 2nd down, 100% on 3rd/4th down), **Explosive Chunk Plays** (`15+` yard passes / `10+` yard runs), scoring play breakdowns, and turnover counts.

### 4. 🏆 Historical Season Recap & Championship Tracker (CFB & NFL)
* **College Football (2004–2026):** Tracks National Champions (BCS & CFP eras), final AP Top 25 rankings, Heisman Trophy winners, and major national award winners (Maxwell, Biletnikoff, Doak Walker, Davey O'Brien, Bednarik, Nagurski, Outland, Thorpe, and Ray Guy).
* **NFL (2004–2026):** Tracks Super Bowl champions, Super Bowl MVPs, NFL Regular Season MVPs, Offensive/Defensive Players of the Year, Rookies of the Year, and conference/division standings.
