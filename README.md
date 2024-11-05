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
  
## 📊 Model Evaluation

The following metrics were used to evaluate model performance:

- **Confusion Matrix**: Used to visualize and evaluate the accuracy of classification by showing the true vs predicted classifications for each class.
- **Accuracy Score**: Measures the overall correctness of the model by calculating the ratio of correct predictions to the total predictions.
- **Silhouette Score**: Applied in clustering analysis to measure how similar each point is to its own cluster compared to other clusters. A higher silhouette score indicates better-defined clusters.

### Model Results

- **Support Vector Machine (SVM)**: SVM achieved an accuracy of X%, providing insights into classification performance across different smartphone price ranges.
- **Decision Tree Classifier**: Decision Tree achieved an accuracy of Y%, showing how well the model can separate classes based on smartphone features.
- **K-Means Clustering**: The optimal number of clusters was determined using the elbow method and validated by the silhouette score, resulting in a silhouette score of Z.

## 🤔 Future Improvements

- **Hyperparameter Tuning**: Experimenting with various parameters to enhance model accuracy and generalization.
- **Feature Engineering**: Adding or transforming features to capture more complex patterns.
- **Other Clustering Algorithms**: Trying out alternative clustering techniques such as DBSCAN or Hierarchical Clustering for comparison.

## 📬 Contact

If you have any questions or suggestions regarding this project, feel free to reach out:

- **Name**: Emanuel Charel Alessando Soge
- **Email**: [212310053@student.ibik.ac.id](mailto:212310053@student.ibik.ac.id)
- **GitHub**: [Charelas](https://github.com/Charelas)

---


