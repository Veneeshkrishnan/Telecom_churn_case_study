# Telecom Churn Case Study
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecom industries experiences an average of 15% to 25% annual churn rate. Given the fact it costs 5-10 times more to acquire a new customer than to retain a existing customer. So customer retention become more important than customer acquisition.


## Table of Contents
* Business Objectives
* Structure of case study
* Insights
* Conclusions
* Technologies used
* References
* contact


## Business Objectives
* For many operators, retaining high profitable customers is the number one business goal.To reduce customer churn, the operators need to predict which customers are high risk of churn.
* The goal is to build a machine learning model that can able to predict the churning customers using the given dataset.

## Structure of case study
* Problem statement
* Business objectives
* Data understanding and cleaning
* Exploratory data analysis
* Data preparation
* Model building and evaluation
  * logistic Regression
  * Gaussian Naive Bayes
  * Random Forest
  * Ada Boost
  * XG Boost
  * KNN
* Important features
* Recommend Strategies and Suggestions



## Insights
* If minutes of usage decreases steadily in the consecutive months, then the customer has high risk of churn.
* Average revenue per user seems to be most important feature in determining churn prediction.
* Less number of high value customer are churing but for last 6 month no new high valued cusotmer is onboarded which is concerning and company should concentrate on that aspect.
* Customers with less than 4 years of tenure are more likely to churn and company should concentrate more on that segment by rolling out new schems to that group.
* Incoming and Outgoing Calls on romaing are strong indicators of churn behaviour.
* If customer is using the services for incoming calls only and has stopped using outgoing calls then he is finding the services very costly and may switch to network where incoming and outgoing services are in reasonable rate.
* If internet speed that customer is getting is good, customer will finsh data soon and recharge it again but if network is poor and speed is not good then customer will not be able to finish it and will not recharge it multiple times. so need to look into areas where mnetwork is poor and customer care is receiving complaints multiple times.
* Recharge amount is very important factor to notice if it starts reducing month by month then it need to be looked as cutomer may not be happy with the services he is getting that is why he started recharging with less amount.
* If all kinds of call and data usage reduces then it is serious concern as customer may be planning to churn and just timepassing for few more days. so company need to look into these ares.

## Conclusion
From the Exploratory data analysis and from the coefficient values of the features obtained from logistic regression, the most important features for predicting the customer churn are:

* ARPU_8 - Average revenue per user for a month.
* ONNET_8 - onnet minutes of usage of the customers for a month.
* OFFNET_8 - offnet minutes of usage of the customers for a month.
* loc_ic_t2m_mou_8 - Local incoming minutes of usage.
* tot_rec_num_8 - Total number of recharge on eighth month
* og_others_8 - outgoing others.
* monthly_2g_8 - monthly 2g on eighth month.
* monthly_3g_8 - monthly 3g on eighth month.
* max_rec_amt_8 - maximum recharge amount on eighth month.
* Sachet_3g_8 - small service packages purchase on eighth month.

## Technologies Used
- Python version 3.8.8
- numpy library version 1.20.1
- pandas library version 1.2.4
- matplotlib library version 3.3.4
- seaborn library version 0.11.1
- scikit-learn library version 0.24.1
- statsmodels version 0.12.2
- imblearn library version 0.9.1
- git version 2.34.0.windows.1


## References
1. https://www.kaggle.com/code/rahulbhargava21/telecom-churn-case-study/notebook#Data-Preparation
2. https://jovian.ai/abhi120490/telecom-churn-case-study
3. https://github.com/ankushhanda/data-science/blob/master/Churn_Prediction/Churn_prediction.ipynb


## Contact
Created by [https://github.com/Veneeshkrishnan] - feel free to contact us!
1. Veneesh -  veneeshkrish96@gmail.com
