# Customer Segmentation using K-means Clustering

This project performs customer segmentation for a retail store using K-means clustering. The segmentation is based on the customers' purchase history, aiming to identify distinct groups for targeted marketing strategies.

## Dataset

The dataset used in this project is from Kaggle: [Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). It contains information about customers including their annual income and spending score.

## Project Steps

1. **Loading the Dataset**: The dataset is loaded into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**: Initial exploration and visualizations are performed to understand the data distribution.
3. **Data Preprocessing**:
   - Handling missing values.
   - Converting categorical data to numeric (Gender).
   - Selecting relevant features for clustering (`Annual Income (k$)` and `Spending Score (1-100)`).
   - Standardizing the features.
   - Applying PCA for visualization.
4. **Optimal Number of Clusters**: The elbow method is used to determine the optimal number of clusters.
5. **Applying K-means**: K-means clustering is applied with the optimal number of clusters.
6. **Visualization**: The clusters are visualized using a scatter plot of the PCA components.
7. **Interpretation**: The clusters are interpreted by analyzing the mean values of features within each cluster.
8. **Output**: The clustered data is saved to a new CSV file.

## Installation

To run the notebook and perform the clustering, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
