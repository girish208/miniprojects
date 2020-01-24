# Take Home Challenge Exercise


## Problem: Rider Retention Prediction

### Part 1 ‑ Exploratory data analysis

## Data
1. A login timestamp table ( "Data/logins.json" ) that has timestamps of user logins in a particular geographic location.
2. A rider table ( "Data/ultimate\_data\_challenge.json" ) with the following columns:
  * city: city this user signed up in


## Approach

### Part 1 ‑ Exploratory data analysis
* Apply time series resmapling method to identify underlying pattern.

### Part 2 ‑ Experiment and metrics design
* Apply hypothesis testing to measure success of this experiment.

### Part 3
1. Apply data wrangling to fix data types and fill missing values and fix outliers if applicable.
2. Define retained rider using time series analysis techniques.
3. Apply exploratory data analysis to find potential correlation between features and target, i.e., whether rider is retained.
4. Apply machine learning with 4 different models:
  * K-Nearest Neighbors
  * Logistic Regression
  * Random Forest
  * Gradient Boosting
5. Analyze models and find predictive features.


## Conclusion
With the exploratory data analysis and predictive model, avg\_rating\_by\_driver, surge\_pct, weekday\_pct and city are key features for predicting rider retention. The models can also be used to maintain / improve the rider retention.

For example, Ultimate can focus more on riders whose sign up city is Astapor since their retention seem not good. Ultimate should also focus more on improving Android application user experience since their retention is not good.

## Deliverables
1. Data wrangling, exploratory data analysis & modeling code in Python notebook.