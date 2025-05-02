# Profitability Analysis: Insights for New Movie Studio

## Project Overview

The movie industry is a highly competitive environment,  and understanding what makes a movie profitable is essential for success. This project explores potential predictor variables the company can leverage in making data-supported decisions for its new movie studio division to optimize profitability. Three datasets are strategically prepared, merged and cleaned for analysis. 
* bom.movie_gross.csv.gz
* tn.movie_budgets.csv.gz
* im.db.zip

    
## Data Preprocessing

Loading datasets, merging DataFrames, handling missing values, dropping duplicates, and feature engineering. 

**Target variable:** profitability = worldwide gross - production budget. 

**Predictor factors:** 

1: Genres: The different genres a movie may belong to (e.g., Action, Comedy, Drama).

2: Season of Release: The season in which the movie was released (e.g., Summer, Fall, Winter).

3: Production Budget: The total budget allocated for the production of a movie.

4: Star Power: Actors and Directors that potentially influence the movie's success.


## Visualizations

**1: Genre:** The most profitable genres are Drama, Comedy, Horror, Thriller, and Action. ![average-profit-by-genre](https://github.com/user-attachments/assets/f1cebcd1-ea4b-47d5-9df5-eac9254f45e2)


**2: Season:** Summer releases tend to generate higher average profits compared to other seasons.![average-movie-profit-by-season](https://github.com/user-attachments/assets/9b691fe2-c35a-405b-aa66-1c5d7e2c05cc)


**3: Star Power:** A movie's profitability is dependent on top-performing talent.![top10-actors-by-total-profit](https://github.com/user-attachments/assets/a0d57b29-4cdc-44ae-9030-3082e9ccbb00)


## Hypothesis Testing Summary

**• Genre:** Statistically significant relationship between genre and pofitability.

**• Season:** No statistically significant relationship between a movie's release season and profitability.

**• Budget:** Weak positive correlation between production budget and profitability.

**• Star Power:** Statistically significant dependence between top talent (directors and actors) and a movie's profitability.


## Business Recommendations

**1. Focus on High-Returning Genres:** Prioritize top-performing genres: Drama, Documentary, Comedy, Horror, Mystery, Thriller and Romance.

**2. Leverage Star Power Selectively:** Cast top-performing actors and directors to increase box office grossing. Strike an effective balance between contracting top-performers and emerging talent to control against budget overshoot and meet market appeal.

**3. Optimize Release Timing:** Schedule major releases in Summer to optimize Box Office grossing.

    
## Next Steps

1: Initialize and diversify professional networks with top-performing actors and directors.

2: launch talent search projects to identify emerging actors with substantial potential.

3: Conduct extensive research on latest technologies (software and hardware) in film production. 

5: Conduct case studies on top-performing studios.
   
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






