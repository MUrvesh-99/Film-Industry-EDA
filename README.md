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
<p align="center">
  <img src="https://github.com/MUrvesh-99/Film-Industry-EDA/blob/main/charts/budget_revenue_trend.png"
       alt="Film-Industry-EDA" width="900">
</p>

<p align="center">
  <img src="https://github.com/MUrvesh-99/Film-Industry-EDA/blob/main/charts/films_according_Year.png"
       alt="Film-Industry-EDA" width="900">
</p>
<p align="center">
  <img src="https://github.com/MUrvesh-99/Film-Industry-EDA/blob/main/charts/language_analysis.png"
       alt="Film-Industry-EDA" width="900">
</p>
<p align="center">
  <img src="https://github.com/MUrvesh-99/Film-Industry-EDA/blob/main/charts/rating_buckets.png"
       alt="Film-Industry-EDA" width="900">
</p>

## Dataset
Source: TMDB Movies Dataset via Kaggle  
Clean dataset: 4,767 films | 24 columns | 3,226 films with complete financial data  
Link: https://www.kaggle.com/datasets/utkarshx27/movies-dataset

## Tech Stack
Python 3 | Pandas | NumPy | Matplotlib | Seaborn
