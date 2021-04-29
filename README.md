# Rainfall_Pred


A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset This project is tested over lot of ml models like  logestic, xgboost, random forest, support vector classifier, etc.. Out of these models random forest and xgboost performed very well giving an AUC score around and ROC score of 87 far better than others. Here due to my system compatibility is very low. So I have done hyperparameter tuning and  the models are giving good accuracy.


# Data Collection:
Rainfall Prediction in Australia dataset from Kaggle


# Data Preprocessing:
> Missing Values Handled by Random Sample imputation to maintain the variance
> Categorical Values like location, wind direction are handled by using Target guided encoding
> Outliers are handled using IQR and boxplot
> Imbalanced Dataset was handled using SMOTE

# Model Creation:
> Different types of models were tried like  random forest, logistic regression, xgboost, support vector machines, knn, decision tree.
> Out of these xgboost, random forest and support vector machines were top 3
> he conclusion were made using classification metrics, accuracy score, roc-auc

# How to run this app
> install all the packages by using the following command
> pip install -r requirements.txt
> Now for the final step. Run the app
> python rainy_app.py



