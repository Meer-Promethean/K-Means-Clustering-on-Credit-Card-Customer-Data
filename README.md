#  K-Means Clustering on Credit Card Customer Data

## Objective
Train a K-Means clustering algorithm on the given dataset to segment credit card customers into different groups based on their spending behavior and demographic features.

## Instructions
1. **Download the Dataset**  
   Download the dataset from [this Kaggle link](https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data/data).

2. **Tasks**  

   ### a. Data Preprocessing
   - Load the dataset and inspect its structure.
   - Handle missing values, if any.
   - Scale the numerical features using an appropriate scaling technique.
   - Encode any categorical variables, if applicable.

   ### b. Exploratory Data Analysis (EDA)
   - Generate summary statistics for the dataset.
   - Visualize relationships or patterns in the data using scatter plots, pair plots, or histograms.

   ### c. K-Means Clustering
   - Use the **KMeans** algorithm from the `sklearn` library.
   - Train the model with the optimal number of clusters.

   ### d. Interpretation
   - Assign cluster labels to the dataset.
   - Visualize the clusters using two or more prominent features (e.g., using PCA for dimensionality reduction if necessary).
   - Analyze and describe the characteristics of each cluster (e.g., high spenders, low spenders, etc.).
