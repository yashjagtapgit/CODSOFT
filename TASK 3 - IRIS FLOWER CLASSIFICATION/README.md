
# TASK 3 - IRIS FLOWER CLASSIFICATION
**Codsoft Data Science Internship**
> Author: Yash Jagtap

> Batch: AUGUST BATCH A67

> Domain: Data Science

## Aim
The aim of this project is to classify iris flowers into three different species (setosa, versicolor, virginica) based on their sepal and petal measurements. The Iris dataset is a widely used dataset for introductory classification tasks in machine learning.

## Libraries Used
The following important libraries were used for this project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.model_selection.train_test_split
- sklearn.linear_model.LogisticRegression
- sklearn.ensemble.RandomForestClassifier
- sklearn.metrics.accuracy_score

## Dataset
The dataset used in this project is the Iris dataset, which consists of 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. Each sample belongs to one of three species.

## Data Exploration and Preprocessing
- The dataset was loaded using pandas and initial exploration was conducted using `df.head()`, `df.info()`, and `df.describe()`.
- No missing values were found, and the dataset was clean and ready for analysis.
- The species column was encoded numerically using Label Encoding.
- The dataset was split into training and testing sets using `train_test_split`.

## Data Visualization
- Various visualizations were created to understand the distribution of the data, including histograms for each feature and a heatmap to show correlations between features.

## Model Training
- Two models were trained: Logistic Regression and Random Forest Classifier.
- The Logistic Regression model achieved an accuracy of 96.19% on the training data and 95.56% on the test data.
- The Random Forest model also performed well, confirming the high separability of the iris species based on the provided features.

## Model Evaluation
- Both models were evaluated on the test data and achieved high accuracy, demonstrating the effectiveness of the chosen features in classifying the iris species.
- The results validate the application of these models in real-world classification tasks with well-defined and separable classes.
