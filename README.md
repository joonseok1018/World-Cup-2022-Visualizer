# ⚽ 2022 World Cup Final: Tactical Heatmap & Spatial Analytics

An interactive football spatial analytics application built with **JavaScript/HTML** and **Python**. This project streams open-source event data from the 2022 FIFA World Cup Final (Argentina vs. France) to calculate spatial action counts, dynamically profile all 35 active players, and render pitch-based density heatmaps.

---

## 🌟 Key Features

* **Dynamic Player Discovery:** Scans the match event stream and dynamically counts all **35 unique players** who logged pitch actions.
* **Interactive Pitch Visualizations:** Maps $X, Y$ coordinate event data onto a standard pitch (120x80 StatsBomb coordinate space).
* **Dual Implementation:**
  * **HTML/JS Dashboard:** Web UI with live player filtering and heatmaps.
  * **Python Script:** Terminal-driven menu with Matplotlib rendering and automatic `.png` saving.

---

## 📊 Dataset Overview

* **Source:** [Hudl / StatsBomb Open Data GitHub Repository](https://github.com/hudl/open-data)
* **Match ID:** `3869151.json` (Argentina vs. France — December 18, 2022)
* **Total Players Tracked:** **35 Players** (17 Argentina, 18 France)
* **Coordinates Scale:** $X \in [0, 120]$, $Y \in [0, 80]$

---

## 🚀 Quick Start

### Option 1: Web Dashboard (HTML & JS)

1. Clone or download this repository.
2. Open `index.html` directly in any web browser (no local server required).
3. Use the top selection menu to search through all **35 players** ranked by on-pitch activity.

---

### Option 2: Python Script

#### Prerequisites
Install the required dependencies using `pip`:

```bash
pip install requests matplotlib
