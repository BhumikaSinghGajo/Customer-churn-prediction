
# Customer Churn Prediction with Machine Learning

The goal of this machine learning project is to forecast customer attrition for a telecom provider. The number of consumers who discontinue using a business's goods or services in a specific time frame is referred to as customer churn. Businesses need to be able to predict customer churn because it keeps customers longer and boosts sales.


## Dataset

The dataset includes account information, service specifics, and demographic data about the customers. The binary variable that represents the customer's churn status is the target variable.

## Methodology

The project was divided into the following steps:

* Data Cleaning and Preprocessing: Preprocessing and cleaning were done on the dataset to get rid of outliers, missing values, and other irregularities.

* Exploratory Data Analysis: Different exploratory data analysis techniques were applied in order to determine how one variable related to another and to the target variable.

* Feature Engineering:To enhance the machine learning models' performance, new features were developed.

* Model Selection: To choose the top-performing machine learning model, a number of models were trained and evaluated.

* Hyperparameter Tuning: The chosen model's hyperparameters were adjusted to maximize performance.

* Model Evaluation: The performance of the final model was assessed using a test dataset.

## Results

The decision tree model that was ultimately used revealed the overfitting issue. Therefore, the randomised search CV on the random forest classifier produced results with an accuracy of 87%, while the grid search CV produced results with an accuracy of 87% and incorrect model predictions of 246/2000.

## Conclusion

The telecom company can use the machine learning model created in this project to forecast customer attrition and take the necessary steps to keep customers. Adding more data sources and streamlining the feature engineering procedure are two more ways to enhance the model.
