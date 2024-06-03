# Identify_Customer_Segments

**Udacity Project Identify Customer Segments**

In this project, you will apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that you will use has been provided by our partners at Bertelsmann Arvato Analytics, and represents a real-life data science task.

**Overview Procees**

*Step 1: Preprocessing*
- Using Udacity_XXX_Subset.csv to find and drop some row and feature base on missing value ...
- Select and Re-Encode Features 

*Step 2: Feature Transformation*
- We apply Feature Scaling (SimpleImputer, StandardScaler) to make sure not exist null value
- Perform Dimensionality Reduction by using PCA.. and find number of components to retain

*Step 3: Clustering*
- Try to find best number cluster by using Udacity_XXX_Subset.csv. We find 19
- Apply it for my customer data
