# Customer Purchasing Behavior & Recommendation System Analysis

##  Project Overview

This project analyzes customer purchasing behavior using data analysis, visualization, clustering, and association rule mining techniques. The objective is to understand customer engagement, shopping satisfaction, recommendation effectiveness, and product relationships to generate actionable business insights for improving Target’s recommendation system.

The project includes:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Customer Segmentation
* K-Means Clustering
* Apriori Algorithm for Product Recommendations
* Behavioral Insights & Business Recommendations

---

#  Objectives

The main objectives of this project are:

* Analyze customer purchasing behavior and browsing habits
* Understand customer satisfaction and recommendation effectiveness
* Identify at-risk customers using segmentation techniques
* Discover relationships between product categories using Apriori Algorithm
* Suggest actionable improvements for recommendation systems

---

#  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Mlxtend
* Jupyter Notebook

---

#  Dataset Information

The dataset contains customer survey responses related to:

* Customer demographics
* Purchase frequency
* Browsing behavior
* Product categories
* Shopping satisfaction
* Recommendation helpfulness
* Review reliability
* Cart abandonment behavior

---

#  Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Removed duplicate and inconsistent entries
* Standardized categorical values
* Converted ordinal variables into numeric format
* Handled missing values
* Renamed misformatted columns
* Prepared data for clustering and association analysis

---

#  Descriptive Behavior Analysis

## Key Findings

### Customer Demographics

* Average customer age ≈ 34 years
* Gender distribution is balanced across all categories

### Purchase Behavior

* Purchase frequency is evenly distributed
* Customers exhibit both frequent and occasional shopping behavior

### Popular Product Categories

Most purchased categories:

* Beauty & Personal Care
* Clothing & Fashion
* Home & Kitchen

### Browsing Behavior

* Many users browse multiple times a day
* Indicates moderate to high platform engagement

### Cart Behavior

* High cart abandonment observed
* Shipping costs and price comparison are major factors

### Satisfaction Analysis

* Shopping satisfaction remains moderate
* Recommendation systems show limited impact on satisfaction

---

#  Customer Segmentation

Customers were segmented into:

## 1. Frequent Buyers

* High purchase frequency
* High satisfaction
* Loyal and engaged customers

## 2. Occasional Shoppers

* Moderate engagement
* Potential for conversion into loyal customers

## 3. At-Risk Customers

* Low satisfaction
* Lower engagement levels
* High risk of churn

---

#  K-Means Clustering

K-Means clustering was applied using behavioral variables such as:

* Purchase Frequency
* Browsing Frequency
* Shopping Satisfaction
* Recommendation Helpfulness
* Rating Accuracy

## Elbow Method

The Elbow Method identified:

* Optimal clusters = 3

## Clustering Insights

The clusters aligned closely with manually created customer segments:

* Engaged Customers
* Moderate Users
* At-Risk Customers

---

#  Apriori Algorithm & Association Rules

Association Rule Mining was performed using the Apriori Algorithm to identify products frequently purchased together.

## Strong Association Rules

Examples:

* Groceries + Others → Clothing
* Home + Others → Clothing
* Groceries + Home → Clothing

## Key Insight

Clothing products act as a strong cross-selling category.

---

#  Visualizations Included

The project includes:

* Bar Charts
* Pie Charts
* Heatmaps
* Boxplots
* Cluster Visualizations

Visualizations were used to analyze:

* Purchase categories
* Browsing frequency
* Shopping satisfaction
* Correlation between recommendation helpfulness and satisfaction

---

#  Business Recommendations

Based on the analysis, the following improvements are suggested:

## Improve Recommendation Quality

* Focus on relevance rather than quantity
* Use customer browsing and purchase history

## Use Apriori-Based Recommendations

* Recommend complementary products dynamically
* Implement “Frequently Bought Together” suggestions

## Reduce Irrelevant Suggestions

* Display fewer but highly relevant recommendations

## Add Explainability

Examples:

* “Recommended based on your browsing history”
* “Customers like you also bought this”

## Target Customer Segments

* Frequent Buyers → Premium products
* Occasional Shoppers → Promotions and offers
* At-Risk Customers → Personalized retention campaigns

---

#  Key Insights

* Recommendation helpfulness has weak correlation with shopping satisfaction
* Reviews have limited impact on rating accuracy
* User engagement is moderate
* Clothing products have strong cross-selling potential
* Improving recommendation relevance is more important than increasing recommendation frequency

---

#  Future Improvements

Potential future enhancements:

* Real-time recommendation system
* Collaborative filtering models
* Deep learning-based recommendation engine
* Advanced sentiment analysis on reviews
* Interactive dashboard deployment

---

#  Project Outputs

The project includes:

* Cleaned Dataset
* Jupyter Notebook
* Visualizations
* Customer Segmentation Results
* Apriori Association Rules
* Final Report

---

#  Conclusion

This project demonstrates how customer behavior analysis, clustering, and association rule mining can provide valuable business insights. The analysis highlights the importance of recommendation relevance, behavioral segmentation, and data-driven cross-selling strategies to improve customer satisfaction and engagement.

