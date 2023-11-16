<h1 align="center">Advanced Clustering Analytics in Enology: A Comprehensive Study of Wine Characteristics Using Machine Learning Techniques</h1>

## Overview

This project, developed by Sai Narayan, implements advanced clustering analytics in the field of enology, utilizing machine learning techniques to study wine characteristics. The project leverages PySpark, a tool for handling big data, to perform clustering using KMeans and BisectingKMeans algorithms. The primary goal is to identify patterns and groupings in wine characteristics, enhancing the understanding of wine quality and classification.

## Program Functionality

1. **Data Loading and Preprocessing:** The project starts by loading wine data into a PySpark DataFrame. It then preprocesses this data using VectorAssembler to convert it into a suitable format for machine learning algorithms.

2. **KMeans Clustering:** Implements KMeans clustering on the preprocessed data. It includes a custom function `fit_kmeans` to facilitate multiple executions with different numbers of clusters.

3. **Clustering Evaluation:** Evaluates the clustering performance using silhouette score and within-cluster sum of squares (WCSS). These metrics help in determining the optimal number of clusters.

4. **Visualization:** Provides functions for visualizing the clustered data in two dimensions, aiding in the interpretation of clustering results.

5. **Hyperparameter Tuning:** Performs a hyperparameter sweep over different values of k (number of clusters) to find the optimal clustering configuration.

6. **Comparative Analysis with BisectingKMeans:** Explores clustering using the BisectingKMeans algorithm, following a similar evaluation and visualization approach.

7. **Application to New Dataset:** Applies the KMeans fitting procedure to a new wine dataset to compare and analyze different clustering behaviors.

## Notes

- The project is designed to be flexible, allowing users to easily modify the number of clusters and other parameters.
- It is a valuable resource for researchers and enthusiasts in the field of wine analytics and machine learning.
- The code is structured to be clear and understandable, making it accessible for users with varying levels of expertise in PySpark and machine learning.

---

# Academic Integrity Statement

Please note that all work included in this project is the original work of the author, and any external sources or references have been properly cited and credited. It is strictly prohibited to copy, reproduce, or use any part of this work without permission from the author.

If you choose to use any part of this work as a reference or resource, you are responsible for ensuring that you do not plagiarize or violate any academic integrity policies or guidelines. The author of this work cannot be held liable for any legal or academic consequences resulting from the misuse or misappropriation of this work.

Any unauthorized copying or use of this work may result in serious consequences, including but not limited to academic penalties, legal action, and damage to personal and professional reputation. Therefore, please use this work only as a reference and always ensure that you properly cite and attribute any sources or references used.
