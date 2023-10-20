# Retail Rationalization Business Clustering

**Overview:**

Store Rationalization is the process of reorganizing a company to improve operational efficiency and reduce costs. Due to the COVID-19 crisis, many retail businesses worldwide had to close their stores. Some companies have focused their investments on digital transformation.

In this case study, we will use a dataset of Starbucks store locations to perform business clustering and rationalization. We will select a specific geographic area, simulate business information for each store (such as cost, capacity, staff), and then perform clustering to optimize store rationalization.

**Table of Contents:**

1. **Import Libraries:** Import necessary libraries and load the dataset.
   
2. **Data Setup:** Select a specific city (Las Vegas) and preprocess the dataset, simulating business information for each store.

3. **Exploratory Data Analysis (EDA):** Analyze the cost distribution and capacity of stores, visualizing them on a map.

4. **Model Building - Clustering and Evaluation:**
    - Determine the optimal number of clusters (k) using the Elbow Method.
    - Perform K-Means clustering and find the real centroids for each cluster.
    - Visualize clusters and centroids on a map.
    
5. **Store Rationalization:**
   - Develop a simple algorithm to rationalize stores within each cluster.
   - Move staff from high-cost stores to low-cost stores until reaching capacity, then close the high-cost stores.
   
6. **Conclusion:** Discuss the results and potential improvements to the store rationalization process.