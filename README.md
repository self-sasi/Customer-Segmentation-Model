# Customer Segmentation README

### About Model
This Jupyter notebook is designed to perform customer data segmentation, likely focusing on understanding different customer behaviors or profiles based on shopping data.

---

### Dependencies
- **numpy**: Numerical operations.
- **pandas**: Data manipulation and analysis.
- **matplotlib & seaborn**: Data visualization.
- **sklearn**: Machine learning algorithms and data preprocessing.
- **mpl_toolkits.mplot3d**: 3D plotting tools.

---

### Steps in the Notebook

1. **Importing Libraries**: The notebook imports numpy, pandas, matplotlib, seaborn, sklearn, and mpl_toolkits for various data analysis tasks.
2. **Data Loading and Preparation**: Customer data is loaded, possibly from 'Mall_Customers.csv', and prepared for analysis.
3. **Data Exploration (Optional)**: The notebook might include steps to explore the data to understand distributions, relationships, or anomalies.
4. **Preprocessing**: Data is cleaned and preprocessed, including scaling and other necessary transformations.
5. **Applying KMeans Clustering**: The KMeans algorithm from sklearn is used to segment customers into groups.
6. **Determining the Number of Clusters**: An elbow plot is likely created to determine the optimal number of clusters.
7. **Cluster Visualization**: Clusters are visualized in a 3D scatter plot using matplotlib's 3D toolkit.
8. **Analysis of Clusters**: Clusters are examined, with potential customizations and interpretations of each cluster.

---

### Screenshots and Model Insights
**Data Snapshot**

<img width="787" alt="Screenshot 2023-12-29 at 11 11 08 PM" src="https://github.com/self-sasi/Customer-Segmentation-Model/assets/140454190/5331cd38-0a5d-4a60-877c-e9ef959b30be">

This screenshot illustrates the initial view of the customer data set, showcasing the first few rows. It includes various customer attributes such as age, annual income, and spending scores, which are crucial for the segmentation process. This snapshot provides a glimpse into the data structure and types, ensuring that all necessary preprocessing steps are considered before moving into the segmentation analysis.

----

**Elbow Plot**

<img width="600" alt="Screenshot 2023-12-29 at 11 11 45 PM" src="https://github.com/self-sasi/Customer-Segmentation-Model/assets/140454190/61f69af7-202a-4ee4-9332-11ce2d660286">

Displayed here is the Elbow Plot, a crucial visualization in determining the optimal number of clusters for KMeans segmentation. By plotting the within-cluster sum of squares (WCSS) against the number of clusters, we look for the 'elbow point' where the rate of decrease sharply changes. This point suggests a suitable number of clusters that balances between the model's complexity and its ability to fit the data. The Elbow Plot is an essential step in ensuring that the segmentation is neither too granular nor too simplified.

----

**3D Cluster Plots**

<img width="645" alt="Screenshot 2023-12-29 at 11 12 14 PM" src="https://github.com/self-sasi/Customer-Segmentation-Model/assets/140454190/3fe300d1-01db-446b-a1fe-ae9c6ec19941">

These 3D scatter plots present the formed clusters from the KMeans algorithm, visualizing the customer segments in a three-dimensional space. Each plot may represent different angles or emphasize various clusters. Typically, axes correspond to significant customer characteristics like age, annual income, and spending scores, helping to interpret the cluster's context. Colors distinguish between clusters, illustrating how each customer segment differs in terms of their feature values. The centroids of the clusters are also marked to denote the average characteristic of each segment. These visualizations are instrumental in understanding the segmentation's practical implications and deriving strategic insights.

---
