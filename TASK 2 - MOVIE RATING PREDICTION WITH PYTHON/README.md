# TASK 2 - MOVIE RATING PREDICTION WITH PYTHON
**Codsoft Data Science Internship**
> Author: Yash Jagtap

> Batch: AUGUST BATCH A67

> Domain: Data Science

## Aim
The aim of this project is to build a model that predicts the rating of a movie based on features like genre, director, and actors. The goal is to analyze historical movie data and develop a model that accurately estimates the rating given to a movie by users or critics.

## Libraries Used
The following important libraries were used for this project:
- numpy
- pandas
- seaborn
- matplotlib.pyplot
- sklearn.model_selection.train_test_split
- sklearn.preprocessing.LabelEncoder
- sklearn.linear_model.LinearRegression
- sklearn.metrics.mean_squared_error

## Dataset
The dataset used in this project was a collection of historical movie data containing features such as movie name, year, genre, director, actors, duration, and rating.

## Data Exploration and Preprocessing
- The dataset was loaded using pandas and explored using `df.info()` and `df.describe()`.
- Missing values were handled by removing rows with missing ratings and imputing missing durations with the median.
- Categorical variables such as 'Director', 'Actor 1', 'Actor 2', 'Actor 3', and 'Genre' were encoded numerically using Label Encoding.
- The dataset was split into training and testing sets for model evaluation.

## Exploratory Data Analysis (EDA)
- Various visualizations were created to explore the distribution of movie ratings, genre distribution, and the influence of directors and actors on ratings using seaborn and matplotlib.
- Correlation analysis was performed to identify the most significant features impacting movie ratings.

## Model Training
- A linear regression model was trained to predict movie ratings based on the selected features.
- The model was fitted using `LinearRegression().fit(X_train, Y_train)` and evaluated using Mean Squared Error.

## Model Evaluation
- The model's performance was evaluated using metrics like Mean Squared Error and R-squared on both training and test datasets.
- Insights gained from the model can be used by stakeholders in the film industry to make informed decisions regarding movie production and marketing.

---
