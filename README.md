# Covid19
This project aims to predict COVID-19 test results based on symptoms and demographic information. It includes data cleaning, preprocessing, exploratory data analysis, machine learning model training, and evaluation.

mporting Libraries: This section imports necessary libraries for data analysis, visualization, and machine learning.

Reading the Data: Reads the dataset from a CSV file into a Pandas DataFrame.

Data Cleaning and Preprocessing: Performs various data cleaning and preprocessing tasks such as handling missing values, converting boolean values to strings, converting string values to lowercase, dropping unnecessary columns, mapping categorical values to numerical representation, and applying one-hot encoding.

Data Visualization: Visualizes the data using seaborn's countplot to explore the distribution of symptoms and demographic factors with respect to COVID-19 outcomes.

Feature Scaling: Scales the features using Min-Max Scaling to ensure that all features have the same scale.

Model Training and Evaluation: Trains machine learning models (Logistic Regression, Random Forest, Support Vector Machine, Decision Tree) on the preprocessed data and evaluates their performance using various evaluation metrics such as accuracy, confusion matrix, classification report, and regression evaluation metrics.

Model Comparison: Compares the performance of different models based on their F1-scores.

Overall, this code provides a thorough analysis of COVID-19 test data and demonstrates the application of machine learning techniques for predicting test outcomes based on symptoms and demographic information.
