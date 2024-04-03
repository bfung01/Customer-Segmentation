# Customer Segmentation Project

This repository contains the code and dataset for a customer segmentation analysis using the KMeans clustering algorithm. The project aims to segment customers into distinct groups based on their behaviors and characteristics to tailor marketing strategies and improve customer service effectively.

## Complimentary Medium Post
Here is a link to my Medium post describing my processes and the insights that can be draw from it. https://medium.com/inst414-data-science-tech/customer-segmentation-bdd7e1053cb3

## Project Structure

- `customers.csv`: This CSV file contains the raw customer data used for the segmentation. The data includes various customer attributes such as Gender, Age, Ever Married, Graduated, Profession, Work Experience, Spending Score, Family Size, and more.
- `segmentation.ipynb`: This Jupyter notebook contains the Python code used for preprocessing the customer data, executing the KMeans clustering algorithm, and analyzing the resulting customer segments.

## Data Preprocessing

The preprocessing steps include reading the customer data, setting an index, dropping unnecessary columns and missing values, encoding categorical variables, and normalizing the data where applicable. These steps are crucial for preparing the data for effective clustering.

## Clustering Analysis

The project employs the elbow method to determine the optimal number of clusters. This method involves plotting the within-cluster sum of squares (WCSS) against the number of clusters and identifying the "elbow point" where the reduction in WCSS becomes less pronounced. Based on this analysis, we chose to segment the customers into four distinct clusters.

## Insights and Observations

The notebook further explores the characteristics and behaviors of customers within each identified cluster, providing insights into their preferences and lifestyle choices. This analysis is instrumental in understanding the diverse needs of our customer base and can inform targeted marketing strategies and product offerings.

## How to Run

To execute this project:
1. Ensure you have Jupyter Notebook installed, or use an IDE that supports `.ipynb` files (e.g., Visual Studio Code, PyCharm).
2. Install the necessary Python packages: `pandas`, `matplotlib`, and `scikit-learn`.
3. Open `segmentation.ipynb` and run the cells sequentially to perform the data preprocessing, execute the KMeans clustering, and analyze the results.
