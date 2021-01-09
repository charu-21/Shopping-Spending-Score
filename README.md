# Shopping-Spending-Score

## Business Problem
Market segmentation is the activity of dividing a broad consumer or business market, normally consisting of existing and potential customers, into sub-groups of consumers based on some type of shared characteristics.
Companies employing customer segmentation operate under the fact that every customer is different and that their marketing efforts would be better served if they target specific, smaller groups with messages that those consumers would find relevant and lead them to buy something. Companies also hope to gain a deeper understanding of their customers' preferences and needs with the idea of discovering what each segment finds most valuable to more accurately tailor marketing materials toward that segment.

Malls or shopping complexes are often indulged in the race to increase their customers and hence making huge profits. To achieve this task machine learning is being applied by many stores already. It is amazing to realize the fact that how machine learning can aid in such ambitions. The shopping complexes make use of their customers’ data and develop ML models to target the right ones. This not only increases sales but also makes the complexes efficient.

## Project Overview
- The objective of project is to Increase sales and hence making huge profits, by identifying and targeting the right set of customers.
- Based on 2 most important features which are Annual Income & Spending Score of the Customers, different clusters are analyzed.
- Using different techniques of clustering under Unsupervised Learning like K-Means Clustering, Sillhoutte Cofficient & Agglomerative Clustering optimal number of clusters anre obtained and analyzed to conclude which customers falls in which category.

## Dataset Description
The dataset represents the Annual Income,Spending Score, Gender,Age of different customers, it includes over 4 features and 200 records to analyze the Customer Segmentation.

## EDA
- Aim was to identify the different type of customers on the basis of two most important features which are Annual Income and Spending Score of the Customers. Therefore rest of the features were dropped.

## Model Building Phase
- From all the three methods of clustering which are:
    - K-Means Clustering
    - Silhoutte Coffecient
    - Agglomerative Clustering
- The optimal number of clusters obtained are five. Thus it can be concluded clearly that there are 5 different set of customers based on "Annual Income" & "Spending Score".

## Observations- Clusters obtained from K-Means 
- From the boxplot we get an idea about different set of customers with respect to their earning and spending. With this we can actually comment what is the relationship between these two features and accordingly it would be helpful for a salesman to Increase sales and hence making huge profits, by identifying and targeting the right set of customers. The 5 clusters so obtained concluded that:
   * Cluster 0: These are the customers, who are earning a lot, However their spending score is very less
   * Cluster 1: Customers who are earning and spending average. 
   * Cluster 2: These are the best set of customers, who are not only earning more but also spending a lot as per thier income.
   * Cluster 3: Customers who are earning less, and spending less.
   * Cluster 4: These are the customers who are earning less, but still spending more
   
 - From above observations we can clearly say that from sales point of view, the target should be on Cluster 0 and Cluster 3.As noted above for Cluster 0, despite of earning a lot, spending score is very less, thus the focus should be to convert such set of customers to Cluster 2 who, with high earnings are spending quiet well.
- With this for Cluster 3, where both earnings and spending score is less, focus should be to convert such set of customers to Cluster 4 who, even with  less earnings are spending more.
 
 - Similarly we can observe and comment about the clusters obtained from Agglomerative Clustering. Though the number of clusters obtained were same as K-Means, but there might be a chance that the interpretation for the same would be slightly different.
  
## Conclusion
Thus we can choose any one method of clustering which suits the best as per the requirement, and further comment on the clusters so formed. Thus the objective of Increasing sales and hence making huge profits, by identifying and targeting the right set of customers could be achieved likewise.







