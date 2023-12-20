# Penguin Clustering Analysis
## Overview

This repository contains Python code for performing clustering analysis on a penguin dataset. The analysis involves two clustering techniques: K-Means and Agglomerative Hierarchical clustering. The goal is to identify patterns and group penguins based on certain features.
## Getting Started
### Prerequisites

Make sure you have the following libraries installed:

    pandas
    numpy
    seaborn
    matplotlib
    scikit-learn
    scipy

### Installation

Clone the repository:

bash

`git clone https://github.com/Junkie0/penguin-clustering.git
cd penguin-clustering`

Install required packages:

bash

`pip install -r requirements.txt`

### Usage

    Run the penguin_clustering.ipynb Jupyter Notebook to perform the analysis step by step.
    Adjust parameters and explore additional visualizations as needed.

### Data

The dataset used for analysis is penguins.csv. It includes information about penguins, such as culmen dimensions, flipper length, body mass, and sex.
Analysis Steps

    1. Data Preprocessing:
        Loading and cleaning the dataset.
        Handling missing values and converting categorical variables.

    2. Outlier Handling:
        Identifying and addressing outliers, specifically in the 'flipper_length_mm' column.

    3. Feature Scaling:
        Standardizing features for consistency.

    4. K-Means Clustering:
        Using the Elbow Method to determine the optimal number of clusters.
        Training the K-Means model and visualizing the results.

    5. Agglomerative Hierarchical Clustering:
        Creating a dendrogram to assist in determining the number of clusters.
        Training the Hierarchical Clustering model and visualizing the results.

### Results

    - Visualizations of clustered penguins based on culmen dimensions.
    - Silhouette scores to assess the quality of clustering.

### Acknowledgments

This analysis is inspired by the desire to explore patterns within penguin species using clustering techniques. Dataset credits to the original source.

Please, Feel free to explore, modify, and enhance the analysis based on your requirements!
" Near Feature"