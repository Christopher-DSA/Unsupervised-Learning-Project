# machine_learning_project-unsupervised-learning

## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

# Process Steps
## Cleaning the data:

---
- Checked for NULL/missing data: no nulls
- Checked for duplicates in the data: no duplicates
- Generated summary statsitics to spot any obvious errrors:
![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/f5ad5388-e8ea-4b9c-b255-a5373dbf648e)
  
## Exploring the Data (what does it all mean?):

---

- Finding out what the numbers in the columns represent in plain english:

####  Meaning of the numbers in the 'region' and 'channel' columns
- There are 2 Channels and 3 regions in this wholesale dataset.
Regions - Lisnon, Oporto or Other (Nominal) (1,2,3)
Channel - Horeca (Hotel/Restaurant/Cafe or Retail channel (Nominal) (1,2)

#### Meaning of the numbers in the item category columns:
- Annual spending (Mauritian Rupee) on the type of product the category represents.
- Mauritius is where this dataset comes from based on the currency used
- Mauritus is a country in East Africa

 #### Meaning of the numbers in the item category columns:

- Annual spending (Mauritian Rupee) on the type of product the category represents.
- Mauritius is where this dataset comes from based on the currency used
- Mauritus is a country in East Africa

Plotting Distrubution of annual sales by product category:
![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/eed086e1-8da2-467d-b217-15b6cdbf5727)

# Part II - KMeans Clustering
![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/d9471382-88a6-4074-ae43-da654194db22)


## Spending ratios by category, grouped by cluster
![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/9385a267-39fa-4a2e-824f-184363288b9c)

![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/6278356c-f390-430e-bf33-edf66b2d98bd)

![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/6a5e5a6a-ba22-4362-b287-21e32e7448d5)

![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/4e3c1589-61c0-40b8-9d05-0cfc5d0a9e9a)

## Each cluster represents a different type of customers spending habits. In this case we have 4 different types of customers:
---

| Cluster | Spending Level  | Shopping Style                                                                                      |
|---------|-----------------|-----------------------------------------------------------------------------------------------------|
| 0       | Medium            | Health-conscious or restaurant owners, balanced with a focus on fresh produce and frozen goods.      |
| 1       | Low             | Possibly prefers processed foods, could be eating out often, low on cleaning supplies.                |
| 2       | High        | Convenience or fast-food oriented, good amount of dairy and high on cleaning supplies.                |
| 3       | Medium            | Convenience store types, moderate spending on groceries and cleaning supplies.                        |


![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/2d71f379-5c84-4bd9-80c5-a94f60ba8e43)


## Hiearchal Clustering

![image](https://github.com/Christopher-DSA/Unsupervised-Learning-Project/assets/132075292/32c83578-b4f5-436a-a917-ea5c7c18fced)
