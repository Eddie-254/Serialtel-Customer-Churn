   # Serialtel-Customer-Churn
## Enhancing Customer Retention through Data-Driven Strategies
![telecom-cx](https://github.com/Eddie-254/Serialtel-Customer-Churn/assets/40391537/e332996a-cbe2-468b-a590-3e4ff10a5b7a)


## Project Overview:
The objective of this project is to build a classification model for predicting customer churn in SyriaTel, a telecommunications company. The project follows the CRISP-DM methodology, consisting of six stages: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment. Through this project, we aim to gain insights into the patterns and factors influencing customer churn and create a predictive model to help mitigate customer attrition.

## Business Understanding:
The main focus of this project is to address customer churn reduction for SyriaTel, the key stakeholder. By accurately predicting customer churn, proactive measures can be implemented to maximize customer retention and optimize profits. The project aims to identify patterns that contribute to customer churn and provide actionable recommendations for effective mitigation strategies.

## Data Understanding:
The dataset comprises 3,333 rows and 21 columns, encompassing various call-related features. These features include the duration of calls, the time of day when calls were made, and the type of calls, such as international or customer service-related calls. The target feature of interest is the churn column, which indicates whether consumers have discontinued or continued using the services. It is important to note that the dataset exhibits class imbalance, which will require appropriate handling methods.
Based on domain knowledge, it is advisable to drop certain columns that are not strong predictors of the target variable. For instance, the phone number variable has no relevance to customer churn in the company.

The majority of values in the dataset are numerical. The summary statistics offer a concise summary of the dataset, providing insights into the range of values observed in each numerical column.
## Requirements
Python 3.x Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
## Data Preparation
In order to prepare the data for modeling, the following steps were taken:

* Outliers in the dataset were removed.
* Highly correlated features were addressed to mitigate multicollinearity.
* Numerical variables were scaled to ensure consistent ranges.
* The class imbalance issue were handled using the SMOTE method.
* Models were constructed to make predictions based on the prepared data.
## Modeling
Three different models, including Logistic Regression, Random Forest, and KNeighbors classifier were trained and evaluated using appropriate evaluation metrics such as accuracy, precision, recall, F1 score, and ROC AUC score.
## Contributors
Edwin Nderitu
