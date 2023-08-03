# Project README

## Introduction

This GitHub repository contains code for a project that analyzes a dataset of songs and performs exploratory data analysis (EDA), unsupervised learning (clustering), and supervised learning (regression) to gain insights and predict song popularity. The project is organized into three Jupyter Notebook files:

- **EDA.ipynb**: This notebook performs exploratory data analysis on the dataset, visualizes relationships between different features, and extracts insights from the data.
- **Unsupervised_Learning.ipynb**: In this notebook, unsupervised learning techniques, specifically K-means clustering, are used to group songs into clusters based on their features.
- **Supervised_Learning.ipynb**: The supervised learning notebook focuses on building a regression model to predict song popularity based on various features.

## Dataset

The dataset used in this project is stored in a file called "dataset.csv". The data contains information about various songs, such as danceability, loudness, energy, duration, and popularity, among others. The dataset is cleaned and preprocessed before applying the different analyses.

## Exploratory Data Analysis (EDA)

The EDA notebook explores the dataset, visualizes relationships between features using scatter plots and bar plots, and extracts insights from the data. Some of the key insights include:

- Danceability: Songs with higher danceability are more likely to have higher energy and loudness. Danceability and tempo have a positive correlation.
- Duration: The longest songs are often around average tempo. Songs with high speechiness are not very long.
- Energy: High-energy songs tend to have higher loudness.
- Loudness: High valence is associated with not having low loudness. Medium instrumentalness or acousticness is also not associated with low loudness.

## Unsupervised Learning (Clustering)

The Unsupervised Learning notebook performs K-means clustering on the dataset to group songs into clusters based on their features. The number of clusters is chosen using the elbow method. The clusters are visualized using scatter plots. The key clusters include:

- Cluster 0: High-energy, high-danceability, high-loudness songs. Happy club music like techno and pop.
- Cluster 1: Melancholic singer-songwriter songs with calm and acoustic characteristics.
- Cluster 2: Similar to Cluster 0 but played in minor. May include rap or other genres with higher speechiness.
- Cluster 3: Instrumental house and techno with high danceability, energy, and loudness.
- Cluster 4: Acoustic songs with low energy and loudness.
- Cluster 5: Live recordings with high energy.

## Supervised Learning (Regression)

The Supervised Learning notebook focuses on building a regression model to predict song popularity based on various features. The dataset is split into training and testing sets. Different regression models, including Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regressor, Gradient Boosting Regressor, and Random Forest Regressor, are compared using cross-validation. Random Forest Regressor is chosen as the best model after hyperparameter tuning.

## How to Use

1. Clone the repository to your local machine using `git clone`.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run each of the Jupyter Notebook files in the following order:
   - EDA.ipynb
   - Unsupervised_Learning.ipynb
   - Supervised_Learning.ipynb
4. Review the results and insights obtained from each notebook.

## Conclusion

This project demonstrates the application of exploratory data analysis, unsupervised learning, and supervised learning techniques to analyze and predict song popularity based on various features. The insights gained from the EDA and the clustering of songs into distinct groups can be valuable for music industry professionals and music enthusiasts alike. Additionally, the regression model can be used to predict the popularity of new songs based on their characteristics.

Feel free to explore the notebooks and the dataset to gain further insights and extend the analysis as needed. If you have any questions or feedback, please feel free to reach out. Happy exploring!
