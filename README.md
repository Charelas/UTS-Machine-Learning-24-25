# 📱 Smartphone Price Prediction and Clustering

Welcome to the **Smartphone Price Prediction and Clustering** project! This repository contains machine learning models and data preprocessing techniques applied to a dataset of smartphone specifications for predicting the `price_range` and exploring clusters within the data.

## 📂 Project Overview

This project demonstrates how to:
1. **Preprocess and clean data**: Handling missing values, scaling features, and selecting features for modeling.
2. **Train and evaluate models** for price range prediction using supervised learning techniques like SVM and Decision Trees.
3. **Perform clustering analysis** using K-Means and evaluate clusters using the silhouette score.

## 🔧 Technologies & Tools

- **Python** for scripting and data analysis
- **Pandas & NumPy** for data manipulation
- **Scikit-learn** for machine learning models and evaluation
- **Matplotlib & Seaborn** for visualization
- **Google Colab** for a cloud-based development environment

## 📈 Dataset

- The dataset is available at [GitHub Link to Dataset](https://raw.githubusercontent.com/isnanmulia/lecture-datasets/main/mobileprice_modified.csv).
- **Attributes**: Contains 20 predictor attributes, and one target attribute, `price_range`, representing smartphone price categories.

## ⚙️ Project Structure

```plaintext
├── data                     # Contains dataset and related files
├── models                   # Directory for saved models and configurations
├── notebooks                # Jupyter/Colab notebooks for analysis and modeling
├── README.md                # Project documentation
└── requirements.txt         # Required packages for running the project
