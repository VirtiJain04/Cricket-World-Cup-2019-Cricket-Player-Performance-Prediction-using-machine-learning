# Cricket-World-Cup-2019-Cricket-Player-Performance-Prediction-using-machine-learning
This project predicts One Day International (ODI) players' performance by employing supervised machine learning techniques, separately forecasting batsmen's run-scoring and bowlers' wicket-taking abilities.

There are two parts which are implemented in separate notebooks. The first is for player performance analysis and the other is for Cricket World Cup Analysis.

# Approach:

Player statistics like average and strike rate are not directly available for each game but are derived from innings data. These attributes include:

* **Batting Attributes**: Innings played, batting average, strike rate, centuries, fifties, and zeros.
* **Bowling Attributes**: Innings bowled, overs bowled, bowling average, bowling strike rate, and four/five-wicket hauls.

# Tasks Completed:

* **Data Pre-processing**: Cleaning data by removing unnecessary features, handling missing values, and encoding categorical features.
* **Model Implementations**: Building supervised machine learning models to predict player performance, evaluating them using accuracy, precision, F1 score, and recall metrics.
  
# Conclusion:

* For Batsman Predictions: Random Forest achieved the highest accuracy (0.86), while KNeighborsRegressor had the lowest accuracy.
* For Bowlers Predictions: Linear Regression yielded the highest accuracy (0.86), while KNeighborsRegressor had the lowest accuracy.
