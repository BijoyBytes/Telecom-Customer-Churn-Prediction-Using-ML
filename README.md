# Customer Churn Prediction using Machine Learning

## Project Overview

**Domain**: Telecom Analytics  
**Tech Stack**: Python | Machine Learning | Scikit-learn | Seaborn  
**ML Type**: Supervised Classification  
**Level**: Intermediate → Industry-Ready  


Customer churn is one of the most critical business problems in subscription-based industries like telecom.
This project focuses on predicting whether a customer is likely to churn, enabling companies to take proactive retention actions before revenue loss occurs.

The project demonstrates a complete end-to-end machine learning workflow, from data cleaning and exploratory analysis to model building, evaluation, and business interpretation.

![Library_project](https://github.com/BijoyBytes/Telecom-Customer-Churn-Prediction-Using-ML/blob/main/churn.jpg)

###  Business Problem
Acquiring new customers is significantly more expensive than retaining existing ones.
By accurately predicting churn, companies can:

* Reduce revenue loss
* Improve customer retention strategies
* Optimize marketing and customer support efforts

###  Solution Approach

1. **Data Understanding**
   * Analyzed customer demographics, services, and account information
2. **Data Preprocessing**
   * Handled missing values
   * Encoded categorical variables
   * Scaled numerical features
3. **Exploratory Data Analysis (EDA)**
   * Identified churn patterns and key influencing factors
   * Visualized correlations and distributions
4. **Model Building**
   * Trained multiple ML models
   * Compared performance using evaluation metrics
5. **Model Evaluation**
   * Accuracy
   * Precision, Recall, F1-score
   * Confusion Matrix
6. **Insights & Recommendations**
   * Identified high-risk churn segments
   * Suggested business actions

###  Model Performance

| Model               | Accuracy                   |
| ------------------- | -------------------------- |
| Decision Tree       | 78%                        |
| Random Forest       | **Best Performance – 84%** |

* Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* ML Techniques: Random Forest, Decision Tree, Feature Engineering, Model Evaluation

###  Key Insights

* **New and short-tenure customers are the most vulnerable to churn**
  Customers with low tenure show significantly higher churn rates, indicating that the first few months are critical for customer retention.

  ➤ **Business Action**: Introduce onboarding programs, welcome offers, and early engagement campaigns for new customers.
  
* **Contract type is one of the strongest predictors of churn**
  Customers on month-to-month contracts churn far more frequently compared to those on 1-year or 2-year contracts.

  ➤ **Business Action**: Encourage long-term contract adoption through discounts, loyalty benefits, or bundled plans.


## Conclusions
This project demonstrates how machine learning can be effectively applied to a real-world telecom churn problem, transforming historical customer data into actionable business insights.

Through comprehensive data preprocessing, exploratory analysis, and model evaluation, the project successfully identifies key churn drivers such as contract type, tenure, and billing behaviour. The final model is capable of flagging high-risk customers in advance, enabling telecom companies to shift from reactive churn handling to proactive customer retention.

