---

# TASK 1 - TITANIC SURVIVAL PREDICTION
**Codsoft Data Science Internship**
> Author: Yash Jagtap

> Batch: AUGUST BATCH A67

> Domain: Data Science

## Aim
The aim of this project is to predict the survival of passengers on the Titanic based on various features such as age, gender, ticket class, fare, and the number of family members onboard. This classic machine learning problem serves as an introduction to classification tasks using logistic regression.

## Libraries Used
The following important libraries were used for this project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.model_selection.train_test_split
- sklearn.linear_model.LogisticRegression
- sklearn.metrics.accuracy_score

## Dataset
The dataset used in this project is the famous Titanic dataset, which contains information about 891 passengers on the Titanic, including their survival status, personal details, and ticket information.

## Data Exploration and Preprocessing
- The dataset was loaded using pandas and initial exploration was conducted using `df.head()`, `df.info()`, and `df.describe()`.
- Missing values in the 'Age' column were replaced with the mean age, and the 'Cabin' column was dropped due to a high percentage of missing data.
- The 'Sex' and 'Embarked' categorical columns were encoded numerically using Label Encoding.
- The dataset was split into training and testing sets using `train_test_split`.

## Model Training
- A logistic regression model was trained using the training data.
- The model was fitted to the data using `LogisticRegression().fit(X_train, Y_train)`.

## Model Evaluation
- The model achieved an accuracy of 80.76% on the training data.
- On the test data, the model achieved an accuracy of 78.21%.
- The predictions were evaluated using accuracy metrics and confusion matrix plots.

## Model Deployment
- The trained model was saved as a `.pkl` file using the `joblib` library for future use.
- A Flask application was set up to deploy the model and make predictions based on user inputs.

---