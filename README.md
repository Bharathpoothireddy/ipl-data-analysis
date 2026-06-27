# 🏏 RCB IPL Performance Analysis — A 5-Day EDA Project

**Exploratory Data Analysis (EDA) of Royal Challengers Bengaluru's journey across all IPL seasons (2008–2024).**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📋 Project Overview

This project is a structured 5-day data analytics deep-dive into RCB's performance in the Indian Premier League. Using ball-by-ball data spanning 17 seasons, I explored team trends, tested common cricket myths, and identified true match-winners.

**Team:** Royal Challengers Bengaluru (RCB)  
**Seasons Covered:** 2008–2024  
**Total Matches Analyzed:** 255  
**Ball-by-Ball Records Processed:** 260,920  

---

## 🔍 Daily Breakdown

| Day | Notebook | Question Answered | Key Finding |
|-----|----------|-------------------|-------------|
| **Day 1** | `01_data_overview.ipynb` | How has RCB performed across all seasons? | Overall win rate: **48.2%** (123 wins, 132 losses) |
| **Day 2** | `02_season_analysis.ipynb` | What does the season-by-season trend look like? | RCB has crossed 50% win rate in only a handful of seasons; 2016 was the peak |
| **Day 3** | `03_toss_analysis.ipynb` | Does winning the toss help RCB win? | Toss advantage is marginal — **~5% difference** between winning and losing the toss |
| **Day 4** | *(Reserved for GitHub polish)* | — | — |
| **Day 5** | `05_player_mvp.ipynb` | Which players are RCB's true match-winners? | Chris Gayle (72.5% runs in wins) & S Aravind (72.9% wickets in wins) are the most impactful |

---

## 📊 Key Insights

- **Overall Win Percentage:** 48.2% — RCB has been a below-50% team historically
- **Toss Myth Busted:** Winning the toss improves win probability by only ~5 percentage points
- **Venue Risk:** Certain stadiums have significantly lower win rates (identified in Day 2)
- **True MVPs:** Not just top scorers — players who perform disproportionately in **wins** matter more
- **Retention Strategy:** Prioritize players with high "Win Contribution %" over raw volume

---

## 🛠 Tech Stack

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib
- **Environment:** Jupyter Notebook
- **Version Control:** GitHub
- **Data Source:** IPL Dataset (Kaggle) — matches.csv + deliveries.csv

---

## 📁 Repository Structure

## 📁 Repository Structure

rcb-ipl-analysis/
├── README.md                  # Project documentation
├── 01_data_overview.ipynb     # Day 1: Data loading, cleaning, overall metrics
├── 02_season_analysis.ipynb   # Day 2: Season-by-season win% trend
├── 03_toss_analysis.ipynb     # Day 3: Toss impact analysis
├── 05_player_mvp.ipynb        # Day 5: Player MVP analysis (batting & bowling)
└── plots/                     # Generated charts and visualizations
    ├── rcb_win_pct.png
    ├── top_10_rcb_players.png
    ├── toss_analysis.png
    └── .gitkeep               # Keeps folder tracked in Git


⚠️ Note: Raw CSV datasets (matches.csv, deliveries.csv) are not included in this repository due to size/licensing. Please download them from Kaggle before running the notebooks.

---

## 🚀 How to Run

1. Clone this repository:    git clone https://github.com/Bharathpoothireddy/rcb-ipl-analysis.git
2. Install dependencies:   pip install pandas numpy matplotlib jupyter
3. Open Jupyter Notebook and run the notebooks in order (Day 1 → Day 2 → Day 3 → Day 5)

---

## 💼 Business Applications

The analytical skills demonstrated in this project translate directly to business contexts:

| Cricket Analysis | Business Equivalent |
|------------------|---------------------|
| Toss impact on match outcome | A/B testing on conversion rates |
| Player performance in wins vs losses | Customer segmentation by lifetime value |
| Venue-based win% | Regional sales performance analysis |
| Season-by-season trends | Year-over-year KPI tracking |

---

## 👤 Author

**Bharath Poothireddy**  
linkedin.com/in/bharath-poothireddy-78a602353

---

This project was built as a learning exercise in Exploratory Data Analysis. Feedback and suggestions are welcome!
