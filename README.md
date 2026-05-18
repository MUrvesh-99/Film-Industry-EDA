# 🎬 Film Industry EDA — Investment & Strategy Insights

## Business Context
Analysis conducted from the perspective of a film investment consultancy 
advising studios and independent producers on budget allocation and production 
strategy. The dataset covers 4,803 films sourced from TMDB via Kaggle.

## Business Questions Investigated
- Which genres deliver the best return on investment?
- Does higher budget guarantee higher revenue?
- Does audience rating correlate with commercial success?
- Which directors consistently deliver profitable films?
- Does runtime affect popularity or rating?
- How has film profitability trended over time?
- Which production companies have the best track record?
- Does original language affect revenue?

## Key Findings
- Animation and Horror deliver the highest median ROI — outperforming 
  big-budget Action films significantly
- Budget and revenue show only moderate correlation — high spend does 
  not reliably predict high return
- Film industry ROI has declined since the early 2000s — budgets are 
  rising faster than revenues
- Non-English films frequently achieve competitive ROI despite lower 
  absolute revenue — supporting the case for international content investment
- Runtime sweet spot for both rating and popularity sits between 
  100 and 150 minutes

## Sample Visualisations
![Genre ROI](genre_roi.png)
![Profitability Trend](profitability_trend.png)

## Dataset
Source: TMDB Movies Dataset via Kaggle  
Clean dataset: 4,767 films | 24 columns | 3,226 films with complete financial data  
Link: https://www.kaggle.com/datasets/utkarshx27/movies-dataset

## Tech Stack
Python 3 | Pandas | NumPy | Matplotlib | Seaborn

## How to Run
1. Clone the repo and open `project_movie_kaggle_.ipynb` in Jupyter Notebook
2. Run all cells in order from top to bottom
