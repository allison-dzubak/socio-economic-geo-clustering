# Project: Use socio-economic factors for geographic clustering

## Overview

- This project contains Allison Dzubak's clustering models to identify countries that are similar to each other based socio-economic factors. The dataset was provided by the MIT Applied Data Science Program.

## Data
- data_description.txt is the data description from the MIT ADSP
- data_orig.csv contains the original house price dataset from Kaggle
- data_minmax.csv contains the MinMax scaled data from notebook 0-Data-Preprocessing.ipynb
- data_norm.csv contains the Normalized data from notebook 0-Data-Preprocessing.ipynb
- data_power.csv contains the Power transformed data from notebook 0-Data-Preprocessing.ipynb
- data_quantile.csv contains the Quantile transformed data from notebook 0-Data-Preprocessing.ipynb
- data_robust.csv contains the Robust scaled data from notebook 0-Data-Preprocessing.ipynb
- data_std.csv contains the Standard scaled data from notebook 0-Data-Preprocessing.ipynb

## Notebooks

### 0-Data-Preprocessing.ipynb 
This notebook contains exploratory data analysis and preprocessing for the MIT ADSP socio-economic geographic dataset

- Explore dataset sizes, structures, features, null/duplicate values, summary statistics
- Perform univariate and bivariate analysis / visualization
- Scale the data
- Save scaled data

### 1-Clustering.ipynb
This notebook contains clustering models for the MIT ADSP socio-economic geographic dataset

- Kmeans clustering + elbow plot / silhouette analysis
- Kmedoids clustering + elbow plot / silhouette analysis
- Gaussian Mixture Model clustering + elbow plot / silhouette analysis
- Hierarchical clustering + rand index comparison 
- Compare clustering methods + generate summary visualizations

