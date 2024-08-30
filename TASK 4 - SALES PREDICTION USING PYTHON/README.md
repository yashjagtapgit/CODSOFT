# TASK 4 - SALES PREDICTION USING PYTHON
**Codsoft Data Science Internship**

> Author: Yash Jagtap

> Batch: AUGUST BATCH A67

> Domain: Data Science

## Aim
The aim of this project is to predict sales based on advertising expenditure in various media channels, such as TV, radio, and newspapers. The project utilizes a simple linear regression model to analyze the relationship between these variables and sales.

## Libraries Used
The following important libraries were used for this project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- statsmodels.api
- sklearn.model_selection.train_test_split

## Dataset
The dataset used in this project includes 200 observations with the following features:
- TV: Advertising expenditure in TV (in thousands of dollars).
- Radio: Advertising expenditure in Radio (in thousands of dollars).
- Newspaper: Advertising expenditure in Newspapers (in thousands of dollars).
- Sales: Sales generated (in thousands of units).

## Data Exploration and Preprocessing
- The dataset was loaded using pandas, and initial exploration was conducted using `df.head()`, `df.info()`, and `df.describe()`.
- Outliers were detected and analyzed using box plots.
- The dataset was split into training and testing sets using `train_test_split`.

## Model Training
- A linear regression model was trained using the training data.
- The model was fitted to the data using `OLS().fit(X_train_sm, y_train)`.

## Model Evaluation
- The model achieved an R-squared value of 0.816 on the training data and 0.792 on the test data.
- The regression line was plotted to visualize the relationship between TV expenditure and sales.

## Model Deployment
- The trained model can be used to predict future sales based on new advertising expenditure data.
