# Udacity Data Scientist Capstone Project

Deliverables: Write-up (Blog) and GitHub Reporsitory
## Project Delivery

- Write-up (Medium Articale) https://medium.com/@yuhuailin0323/customer-segmentation-with-k-means-clustering-bcabee0fd234
- GitHub Repository with notebook

## Project Definiton

### Project Overview
This project identifies 3 main customer segments with K-Means clustering: Low-Value Low-Frequency, High-Value Low-Frequency, and Low-Value High-Frequency Users. Furthermore, sub-segmentation and prioritization of the clusters are based on recency. 

The variable selection process for clustering is done by both PCA and business intuition. The clusters generated are evaluated with Silhouette Coefficient and statistical analysis. In following up with this, recommendations for marketing reactivation is provided based on recency and characteristics of different segments.

### Problem Statement

A food delivery company X would like to find pattenrs and insights in the user data and intend to create customized marketing campaign to reactivate based on a user's status. Find insights in the data and try to cluster the users based on their characteristics and behaviours. 


### Data Source

Public Customer Order Data
https://www.kaggle.com/datasets/asaumya/customer-order-data

### Metrics

In this analysis, Silhouette Coefficient and statistical analysis is used to evaluate the performance of the clusters generated. Elbow method is used to decide the number of clusters.

### Analysis

See the notebook for in-depth EDA, visualizatation and statistical data analysis

### Data Preprocessing

The following techniques are used:
- Missing Value Imputation
- Outlier Removal
- Scaling/Centering

### Result, Justification

See the medium blog on why some features are not selected as part of the clustering

