# Rainfall_Pred


A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset This project is tested over lot of ml models like  logestic, xgboost, random forest, support vector classifier, etc.. Out of these models random forest and xgboost performed very well giving an AUC score around and ROC score of 87 far better than others. Here due to my system compatibility is very low. So I have done hyperparameter tuning and  the models are giving good accuracy.


# Data Collection:
Rainfall Prediction in Australia dataset from Kaggle: 
https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

# Data Preprocessing:
1. Missing Values Handled by Random Sample imputation to maintain the variance
2. Categorical Values like location, wind direction are handled by using Target guided encoding
3. Outliers are handled using IQR and boxplot
4. Imbalanced Dataset was handled using SMOTE


# Model Creation:
1. Different types of models were tried like  random forest, logistic regression, xgboost, support vector machines, knn, decision tree.
2. Out of these xgboost, random forest and support vector machines were top 3
3. The conclusion were made using classification metrics, accuracy score, roc-auc

# How to run this app
1. install all the packages by using the following command
2. pip install -r requirements.txt
3. Now for the final step. Run the app
4. python rainy_app.py



