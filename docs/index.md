# Customer Churn Prediction
<p align ="center">
   <img src = "images/churn rate.jpg" width="1000" 
     height="400">
 </p>
 
## [Detailed Project Link](https://nbviewer.org/github/Emmanuel-Nti/customer_churn_prediction_and_retention_strategy/blob/master/customer_churn_nti.ipynb)

#### How I Approached the Project
- Importation of the data and libraries
- Preprocessed the data and carried out exploratory data analysis 
- Built a model to predict customer churn
- Classified customers into clusters
- Conclusion and recommendations
 
#### Cluster of Customers
Customers can be optimally classified into 5 clusters
<p align ="center">
   <img src = "images/clusters.PNG">
 </p>
 
#### Churn Prediction 
Targeting the top 40% of the custmers, we would capture about 95% of clients who would churn.
 <p align ="center">
   <img src = "images/cummulative gains.PNG">
 </p>
 
#### General Findings
- Total number of customers who live near the gym are 5 times more than customers who live far away. More than 50% of customers who do not stay closer to the gym churn while less than half of those who live closer to the gym churn.
- More than half of the customers are employees of a partner company. About 50% of non partner customers churn. Only about 20% of customers from partner companies churn.
- Customers whose joined the gym without promo friends are more than those who joined via promo friend. However, customers who join gym via promo friends are less likely to churn than those who join without a promo friend.
- Share of customers who signed 1 month contract are more than those who signed 6 and 12 months contract. No customer signed a three-month contract. More than 70% of customers who sign 1 month contract churn. less than 5% of customers who sign 12 months contract churn.
- Younger people are more likely to churn than older people.
- Old customers are less likely to churn than new customers.
- There are optimally 5 cluster of customers.
- Churn rates differ among clusters. Clusters 3 and 4 are more prone to leaving, clusters 1 and 2 are more loyal.
- Overall, churn rate is about 27%.
- About 95% of churners are captured in the top 40% of the custmers.

#### Recommendations
- Optimally minimize customer churn with a promotion package targeting the top 40% of customers; this can boost customer retention up to about 95%.
- Encourage customers to sign 12 months contract to reduce churn rate.
- Pay much attention to customers in Clusters 3 and 4 as they are more prone to leaving.
- Introduce loyalty programs.

#### Software and Tools
![](https://img.shields.io/badge/Python-Pandas-informational?style=flat&color=2bbc8a)
![](https://img.shields.io/badge/Numpy-Seaborn-informational?style=flat&color=2bbc8a)
![](https://img.shields.io/badge/Scikit_learn-Matplotlib-informational?style=flat&color=2bbc8a)
![](https://img.shields.io/badge/Scipy-Scikit_plot-informational?style=flat&color=2bbc8a)
