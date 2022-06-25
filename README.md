# CUSTOMER-SEGMENTATION-UNSUPERVISED-ML

**Problem Statement**

Problem Description In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Data Description**

Attribute Information:

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

- Description: Product (item) name. Nominal.

- Quantity: The quantities of each product (item) per transaction. Numeric.

- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.

- UnitPrice: Unit price. Numeric, Product price per unit in sterling.

- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

- Country: Country name. Nominal, the name of the country where each customer resides.

## Exploratory Data Analysis

- Handeling Null Values

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/3b1a3fb4b2f58b21f25763edc10871784e7a765b/Images/Handeling%20Null%20Values.png)

- Monthly purchasing stats

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/3b1a3fb4b2f58b21f25763edc10871784e7a765b/Images/Monthly%20purchasing%20stats.png)

- Week day purchasing stats.png

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/3b1a3fb4b2f58b21f25763edc10871784e7a765b/Images/Week%20day%20purchasing%20stats.png)

- Correlation

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/6ed837cff04e26dc21649006f9d1380f7c2cb825/Images/Correlation.PNG)

- plotting cluster

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/6ed837cff04e26dc21649006f9d1380f7c2cb825/Images/plotting%20cluster.PNG)

- with 3 clusters

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/6ed837cff04e26dc21649006f9d1380f7c2cb825/Images/final.PNG)

- Models

![alt text](https://github.com/hariranjanmeena/CUSTOMER-SEGMENTATION-UNSUPERVISED-ML/blob/6ed837cff04e26dc21649006f9d1380f7c2cb825/Images/Models.PNG)


### Observations/Inferences/Conclusion:

1. Three Clusters (Customer Segments):

Carefully examining the three cluster classification, I observe following groups of customers:

- **High value customer:** 'Cluster 2' is the high value customer segment for the online retails store as the customers in this group place the highest value orders with a very high relative frequency than other members. They are also the ones who have transacted the most recently.

- **Medium value customer:** 'Cluster 0' appears to be the medium valued customer segment. These customers place an order of a considerable amount, though not as much as high valued customers, but still quite higher than low valued customers. Also, their orders are relatively more frequent than the lowest value segment.

- **Low value customer:** It is quite evident that 'Cluster 1' has customers who rarely shop and when they order, their orders are pretty low valued. Apart from the numbers, the visualization of clusters in Silhoutte Analysis show that all three customer segments are quite distinct with very less overlapp between them. The general trend resonated in these 3 clusters is that high monetary value is correlated with high frequency of orders and more recent ones.

2. Five Clusters (Customer Segments):

In five clusters, we find the following customer segments:

- **Overall high valued customers:** 'Cluster 0' is the typical high value customer who has shopped recently and shops regularly for high value orders.

- **High monetary value but less frequent:** 'Cluster 1' represents a peculiar customer segment who place quite a high valued order but do not do so frequently or have not done much recently. But, these customers do hold a lot of promise if targeted to improve sales.

- **Medium value - low frequency - recent customers:** The customers from 'Cluster 4' have recently placed medium valued orders but do not do so frequently.

- **Medium value - low frequency - older customers:** The customers from 'Cluster 3' happen to place medium valued orders quite a long time ago and they do not do so frequently.

- **Low valued customers:** 'Cluster 2' is the segment of customers who have not shopped in the longest time, nor do they shop frequently and their orders are of the lowest values. The visualization of clusters in Silhoutte Analysis show some overlapp between the customer segments. However, the dataset does not distinguish between wholesale and retail customers, it is quite likely that high value frequent clients are the wholesale dealers and medium/ low valued ones are individual retail purchasers.
