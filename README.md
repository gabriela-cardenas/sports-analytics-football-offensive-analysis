# Offensive Performance and Home Advantage in European Football

## Overview

This project explores offensive performance and match outcomes across European football leagues using historical match data stored in a relational database.

The analysis focuses on identifying goal-scoring patterns, evaluating home advantage, and comparing offensive production across teams.

## Objective

- Analyze differences in goal production across leagues  
- Evaluate the strength of home advantage  
- Identify top-performing offensive teams  

## Dataset

The dataset contains historical football match data from multiple European leagues.

Key tables used:
- Match  
- League  
- Team  

Data was extracted using SQL and analyzed using Python (pandas).

##  Tools & Technologies

- Python  
- Pandas  
- SQLite  
- Matplotlib  
- Jupyter Notebook  

## Analysis

### 1. Goal Patterns Across Leagues

- Average goals per match are relatively consistent across leagues  
- No strong outliers observed  
- Offensive output is similar across competitions  

 ![Goals by League](images/goals_by_league.png)

### 2. Home Advantage

- Home teams win ~46% of matches  
- Away teams win ~29%  
- Draws account for ~25%  

- Strong home advantage observed  
- However, over 50% of matches do not result in a home win  

 ![Match Results](images/match_results_distribution.png)

### 3. Top Scoring Teams

- FC Barcelona, Real Madrid, and Celtic rank among the top  
- Offensive output is concentrated among top clubs  
- Reflects competitive imbalance in leagues  

 ![Top Teams](images/top_scoring_teams.png)

## Key Insights

- Goal-scoring patterns are consistent across leagues  
- Home advantage is significant but not decisive  
- A small number of teams dominate offensive production  

## Limitations

- Does not include expected goals (xG)  
- No player-level performance analysis  
- Limited temporal analysis  

## Next Steps

- Incorporate xG for deeper analysis  
- Add player-level data  
- Analyze trends over time  
- Expand to defensive metrics  

## Author

Gabriela Cárdenas  
Aspiring Sports Data Scientist 
