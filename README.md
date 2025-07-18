# IPL Auction Analysis & Forecasting (2021–2024)

This project analyzes data from IPL auctions between 2021 and 2024 to uncover insights into player valuation, performance, and selection trends. Using statistical modeling and visual analytics, we explore how auction prices relate to actual performance and develop models to forecast outcomes like matches played, runs scored, and wickets taken.

The project also investigates patterns based on player type (batter, bowler, all-rounder), overseas vs. Indian status, and year-wise team dynamics. The goal is to bridge auction economics with on-field results, using data science tools to understand and predict what makes a successful IPL investment.


## Key Questions Explored

- How well do auction prices reflect player performance?
- Which features best predict a player's number of matches, runs, or wickets?
- Are overseas players over- or under-valued compared to Indian players?
- What patterns exist across different roles (batter, bowler, all-rounder) over time?


## Repository Structure

ipl-auction-analysis/
- IPL_Auction_Analysis_and_Forecasting.ipynb
- IPL_2021_2024.csv 
- requirements.txt
- README.md 




## Methodology Overview

### Data Source
- Custom-compiled dataset from IPL auction data (2021–2024), including player names, types, nationality, auction year, auction price, team, and performance stats (matches, runs, wickets).

### Preprocessing
- Removed duplicate entries, missing values, and aligned auction years with performance years.
- Normalized data for analysis (e.g., scaling prices, encoding categorical variables).

### Exploratory Data Analysis
- Visualized auction trends across years and teams.
- Compared price distributions for overseas vs. Indian players.
- Analyzed performance by player role (batting vs. bowling vs. all-rounders).

### Modeling & Forecasting
- Built linear regression models and generalized additive models (GAMs) to predict:
  - Number of matches played
  - Runs scored
  - Wickets taken
- Assessed model accuracy using RMSE, R², and residual plots.
- Performed bootstrapping to evaluate variability and stability.


## Tools & Libraries

- `pandas`, `numpy` – Data cleaning and manipulation  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – Regression modeling  
- `statsmodels` – Statistical analysis  
- `pygam` – Generalized additive models  
- `scipy` – Hypothesis testing  
- `jupyter` – Notebook-based workflow  


## Key Insights

- Auction price moderately correlates with match count but weakly with actual runs or wickets.
- Player role significantly impacts valuation—bowlers and all-rounders show different price-performance dynamics.
- Overseas players tend to have higher prices on average, though performance varies year to year.
- GAMs provided smoother and often more interpretable performance predictions than linear regression alone.


## References:

Data adapted and cleaned from IPL official sources and player performance statistics.

Project developed as part of a coursework in statistical modeling and forecasting.

## Contributors
This project was collaboratively developed by:

Meghna Nag, MS in Data Science, University of Colorado Boulder
meghna.nag@colorado.edu

Madhumitha Somasundaram, MS in Data Science, University of Colorado Boulder
madhumitha.somasundaram@colorado.edu


