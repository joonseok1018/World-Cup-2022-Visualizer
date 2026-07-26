# ⚽ World Cup 2022 Tactical Heatmap & Analytics Dashboard

An interactive, web-based tactical dashboard for analyzing event-level data from the FIFA World Cup 2022. Built with React and powered by **StatsBomb Open Data**, this application enables side-by-side team comparisons, detailed individual player metrics, and dynamic spatial heatmaps overlaid on a pitch layout.

---

## 🌟 Key Features

### ⚔️ Team vs Team Comparison Matrix
- **Attacking Metrics:** Goals scored vs. Expected Goals ($xG$), total shots, and shots on target.
- **Possession & Volume:** Total on-ball touches and pass completion percentage.
- **Defensive & Discipline:** Defensive actions (tackles, interceptions, blocks, recoveries), total fouls committed, and discipline cards.

### 👤 Individual Player Analytics
- **Match Output:** Goals, assists, expected goals ($xG$), shots, and key passes (shot assists).
- **Time & Volume:** Total minutes played, total touches, and normalized **Touches per 90 minutes**.
- **Passing Efficiency:** Completed passes vs. total attempts with percentage accuracy.

### 🗺️ Dynamic Pitch & Spatial Heatmap
- **Event Filtering:** Filter pitch actions by **All Actions**, **Passes Only**, or **Shots Only**.
- **Dual Layering:** Blurred heatmap density underlying precise event touch points.
- **Color-Coded Legend:** Visual distinction between passes, shots, and general on-ball touches.

---

## 🛠️ Tech Stack & Dependencies

- **Frontend Framework:** React 18
- **Data Source:** [StatsBomb Open Data Repository](https://github.com/statsbomb/open-data)
- **Styling:** CSS3 (Custom CSS variables with Dark Mode / Tactical Board theme)
- **Compiler:** Babel Standalone (In-browser JSX compilation for quick single-file setup)

---

## 🚀 Quick Start

Because this dashboard is built as a self-contained, single-file web application, no complex build tools or `npm install` steps are required to get started.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/world-cup-2022-dashboard.git](https://github.com/your-username/world-cup-2022-dashboard.git)
   cd world-cup-2022-dashboard
