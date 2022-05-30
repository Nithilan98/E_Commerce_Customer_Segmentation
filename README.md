# E_Commerce_Customer_Segmentation
## Problem Statement

As an e-commerce platform, it is very important to profile your customers, dividing your clientele base into groups based on their needs and expectations. Grouping will help us come up with dedicated marketing strategies and will aid us in recommending products to different user bases. In this project, we are interested in analyzing the content of an E-commerce database that lists purchases made by ∼4000 customers over a period of one year (1/12/2010 to 9/12/2011). Based on this analysis, we would like to develop models to group the 4000 customers into different buckets. ***Such a model must take into account the similarity between the products purchased between the users*** (i.e. a user might purchase 2 different products which are very similar to each other), the spending patterns of a user, their meta information, etc. 

## Data
The data is available here. https://drive.google.com/file/d/1yPthiU42dZv6ju81H5gul_TWmugG71KF/view?usp=sharing

## Minimum Requirements
The end objective of the participant is to come up with customer segmentations that take into account all the information that is presented in the dataset. The participant is expected to use NLP techniques to find similarity between the products. 

## Project Overview 

From the E-Commerce transaction data, only unique values from the Product Description column were taken and Natural Language Processing techniques were applied to convert to numerical data

Then K-Means clustering is applied to get 12 Product Categories from the Product Description data

Then using the Product Categories , I tried to group the customers into different clusters using similarity between products purchased between the users

For this, I have grouped the data using Customer_ID to get a single row data for each customer. Then K-Means clustering is applied to get 6 Customer categories (clusters)

Then Data Visualization like Avg UnitPrice per cluster, Avg Quantity of products per cluster is calculated and the Product Categories present in each Customer Category is also shown

This kind of customer segmentation will help in coming up with dedicated marketing strategies like Targeted discounts, Targeted Ads, Special offers and will aid us in recommending products to different user bases
