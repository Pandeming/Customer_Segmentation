# Customer_Segmentation

CONTENTS:

Capstone 3 Final Report (.docx)

Slide Deck (.pptx)

Python Code (.ipynb):

	01. Data Wrangling

	02. Modeling

Data files:

	online_retail_II.xlsx - original full dataset

	orders.csv - full data grouped by invoice ID

	customers.csv - orders grouped by customer ID

	log_customers.csv - log-transformed data for modeling

	final_labeled.csv - customer data with cluster labels
	
OVERVIEW:

In this project, I compared several different unsupervised clustering models to find the best customer segmentation for an online retailer based on customer transaction history. The three best models all used K-Means clustering: a 4-cluster model using only RFM features for each customer, a 3-cluster model using RFM plus 4 other calculated features (described below), and a 6-cluster model that used RFM plus one additional feature describing the average time between orders for each customer.

Each of these models offers a reasonable segmentation of customers based on their purchasing behavior, though the results could lead to different strategies in marketing for certain customers. All three models will be presented, highlighting some similarities and differences between the resulting segments, so that company leadership can make an informed decision on the best strategy to pursue.