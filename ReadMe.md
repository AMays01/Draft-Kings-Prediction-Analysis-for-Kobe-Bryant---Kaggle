## Draft Kings Analysis For Kobe Bryant 
### 
Alonzo Mays<br>
Mark Harris<br> 
Brian Rubin

## Problem Statement
Draft Kings has hired us to expand on the live betting odds segment of their online app.  We have been tasked to find a model that can predict the most favorable conditions for scoring a basket.  We will use data from the Kobe Bryant Kaggle dataset to see if we can predict a successful score.

## Data Dictionary
<a href='https://www.kaggle.com/c/kobe-bryant-shot-selection/data'> Kobe Bryant Kaggle</a>

|                    |
|--------------------|
| combined_shot_type |
| game_event_id      |
| lat                |
| loc_x              |
| loc_y              |
| lon                |
| minutes_remaining  |
| period             |
| playoffs           |
| season             |
| seconds_remining   |
| shot_distance      |
| shot_made_flag     |
| shot_type          |
| shot_zone_area     |
| shot_zone_basic    |
| shot_zone_range    |
| team_id            |
| team_name          |
| game_date          |
| matchup            |
| opponent           |
| shot_id            |
| game_id            |
| action type        |


## EDA
We looked at the relationship between shot percentage and percentage on the floor and shot type.  We engineered features for home and road games and day of the year.
## Model Selection
The models used for this dataset include Logistic Regression, Support Vector Machines, MultinomialNB. Our baseline model had a training score of 54.6% and testing score of 57%.

## Conclusion
Were able to increase our baseline model by 10% to 67% using the Logistic Regression model.  We recommend Draft Kings to focus on the players shot selection and location on floor of shooting player. 
