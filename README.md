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


### Data Source & Column Description

Public Customer Order Data
https://www.kaggle.com/datasets/asaumya/customer-order-data

Here is a brief overview and explaination of each column 

- `user_id` - unique idenfitication of each user
- `registration_date` - The date since the user completed the registration
- `registration_country` - Country where the user is located in
- `number_of_orders` - number of orders a user made in the timeframe
- `num_orders_delivery` - number of delivery orders a user made
- `num_orders_takeaway` - number of takeaway orders a user made
- `first_order_day`	- Date of the first order
- `last_purchase_day` - Date of the last order
- `breakfast_orders` - # of breakfast orders of a user
- `lunch_orders` - # of lunch orders of a user
- `evening_orders` - # of evening orders of a user
- `dinner_orders` - # of dinner orders of a user
- `late_night_orders` - # of late night orders of a user
- `total_order_values` - total order value of a user in EUR
- `distinct_restaurant_count` - total number of distinct restaurants a user ever odered from
- `min_order_value` - minimun order value of a user
- `max_order_value` - maximum order value of a user
- `avg_order_value` - Avg. order value of a user
- `preferred_device` - User’s preferred device used
- `ios_orders` - # of orders made on an iOS device
- `web_orders` - # of orders made on a website
- `android_orders` - # of orders made on an Android device
- `preferred_restaurant_types` - An Array containing the preferred restaurant type of a user
- `user_has_valid_payment_method` - Boolean column indicating whether a user had valid payment method or not
- `most_common_hour_of_the_day_to_order`
- `most_common_weekday_to_order`
- `avg_days_between_orders` - Avg. # of days between order of a users. If there is only 1 order, then the value will be Null.
- `median_days_between_orders` - Median. # of days between order of a users. If there is only 1 order, then the value will be Null.
- `average_delivery_distance` - Delivary distance in Kilometers.
- `num_orders_by_store_type` - # of orders by the store type

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

