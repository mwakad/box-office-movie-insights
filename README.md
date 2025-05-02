# Profitability Analysis: Insights for New Movie Studio

## Project Overview

The film industry is a highly competitive environment,  and understanding what makes a movie profitable is essential for success. This project explores potential predictor variables a company planning to enter the industry can leverage in making data-supported decisions for its new movie studio division to optimize profitability. Three datasets are strategically prepared, merged and cleaned for analysis. 
* bom.movie_gross.csv.gz
* tn.movie_budgets.csv.gz
* im.db.zip

    
## Data Preprocessing

Loading datasets, merging DataFrames, handling missing values, dropping duplicates, and feature engineering. 

**Target variable:** profitability = worldwide gross - production budget. 

**Predictor factors:** 

1: _Genres_: The different genres a movie may belong to (e.g., Action, Comedy, Drama).

2: _Season_: The season in which a movie is released (e.g., Summer, Fall, Winter).

3: _Production Budget_: The total production budget for a movie.

4: _Star Power_: Actors and Directors that potentially influence a movie's success.


## Visualizations

**1: Genre:** The most profitable genres are Drama, Documentary, Comedy, Horror, Mystery, Thriller, and Romance.![average-profit-by-genre](https://github.com/user-attachments/assets/eee4089c-c797-4784-be26-dacfc91fecd5)
 


**2: Season:** Summer releases tend to generate higher profits on average compared to other seasons.![average-movie-profit-by-season](https://github.com/user-attachments/assets/817bbad7-114c-4c9d-95d5-f207653ae963)



**3: Star Power:** A movie's profitability is dependent on top-performing talent.![top10-actors-by-total-profit](https://github.com/user-attachments/assets/558e3252-2dc5-4e52-83c5-c5617d62a280)



## Hypothesis Testing Summary

**• Genre:** Statistically significant relationship between genre and profitability.

**• Season:** No statistically significant relationship between a movie's release season and profitability.

**• Budget:** Weak positive correlation between production budget and profitability.

**• Star Power:** Statistically significant dependence between top talent (directors and actors) and a movie's profitability.


## Business Recommendations

**1. Focus on High-Returning Genres:** Prioritize top-performing genres: Drama, Documentary, Comedy, Horror, Mystery, Thriller and Romance.

**2. Leverage Star Power Selectively:** Cast top-performing actors and directors to increase box office grossing. Strike an effective balance between contracting top-performers and emerging talent to control against budget overshoot and meet market appeal.

**3. Optimize Release Timing:** Schedule major releases in Summer to optimize Box Office grossing.

    
## Next Steps

**1:** Initialize and diversify professional networks with top-performing actors and directors.

**2:** launch talent search projects to identify emerging actors with substantial potential.

**3:** Conduct extensive research on latest technologies (software and hardware) in film production. 

**4:** Conduct case studies on top-performing studios.

   
## Contributors

Abdirahman Yussuf.

Daniel Mwaka.

Eliana Kariuki.

Gerald Wanjala.

Marion Osong.


## Repository Structure

├─ images

├── notebooks

├── zipped-data

├── README.md

├── index.ipynb

└── presentation.pdf






