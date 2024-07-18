# K-Means Clustering from Scratch

This repository contains the implementation of the K-Means clustering algorithm from scratch using object-oriented programming principles and numpy. The algorithm is applied to a dataset of US Colleges statistics to cluster universities based on various attributes.

## Objective

The objective of this assignment is to deepen understanding of the K-Means clustering algorithm by implementing it from scratch. This involves creating a custom KMeans class with methods similar to sklearn's API, including `fit`, `transform`, `predict`, `fit_transform`, and `fit_predict`.

## Dataset

The dataset used in this project contains statistics for a large number of US Colleges from the 1995 issue of US News and World Report. It includes 777 observations on 18 variables such as number of applications, acceptance rate, tuition costs, and faculty statistics.

[Download Dataset](https://drive.google.com/file/d/1IqSv-q8bE3Fa5n93ZB7-Jza0DffC3TK4/view?usp=sharing)

### Data Preprocessing

1. **Handling Missing Values:** Perform necessary steps to handle any missing values in the dataset.
2. **Scaling Numerical Features:** Normalize or standardize numerical features as required.
3. **Encoding Categorical Variables:** If applicable, encode categorical variables using suitable techniques.

### Implementing K-Means from Scratch

1. **KMeans Class:**
   - Parameters include the number of clusters (K), convergence tolerance, and maximum number of iterations.
   - Attributes include `cluster_centers_`, `labels_`, `n_iter_`, and `inertia_`.
   - Methods include `fit`, `transform`, `predict`, `fit_transform`, and `fit_predict`.

### Testing and Validation

1. Implement the custom KMeans class and validate its correctness by comparing results with sklearn's KMeans implementation.
2. Experiment with different values of K (number of clusters) and choose an optimal value based on evaluation metrics such as silhouette score or elbow method.
3. Compare clustering results with the `Private` attribute in the dataset to assess cluster interpretability.

### Analysis and Interpretation

1. Visualize clusters using scatter plots or other appropriate plots to gain insights into data distribution and cluster separability.
2. Discuss findings, limitations, and implications of using K-Means clustering for this dataset.
