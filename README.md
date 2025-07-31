# ML_Trips_Travel.Com_Random_forest

1) Problem statement.
"Trips & Travel.Com" company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering * Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

2) Data Collection.
The Dataset is collected from https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction The data consists of 20 column and 4888 rows

project:
 This project aims to predict whether a customer will accept a holiday package offer (ProdTaken) based on various customer details like age, gender, travel history, and preferences. The dataset includes both categorical and numerical features. We cleaned the data by checking missing values, imputing them properly, and also created a few new columns to make the data more useful. Then, we used a ColumnTransformer with a Pipeline to preprocess the data (handling both categorical and numerical columns), and trained a Random Forest Classifier. We split the data into training and testing sets (70-30 split) and evaluated the model using accuracy, F1-score, confusion matrix, and ROC AUC curve. We also tuned the model using GridSearchCV with multiple hyperparameters. After tuning, the model achieved a test accuracy of around 91% and gave strong results in identifying customers who are likely to take the holiday package. We also checked which features were most important for the model’s decisions, which can help in real-world marketing. Overall, this project shows a complete classification workflow using Random Forest in a clean and reusable way.

1.Explored the data (EDA + visualizations).

2.Cleaned & preprocessed the data using pipelines (handled missing values, encoded categoricals, scaled numerics).

3.Split into train/test sets.

4.Trained a Random Forest Classifier.

5.Evaluated with accuracy, F1, classification report, confusion matrix.

6.Plotted ROC AUC Curve to understand class separation.

7.Tuned using GridSearchCV with F1 score focus (to address imbalance).

8.Re-evaluated performance.

9.Interpreted Feature Importances to gain business insights.
 
