# 🌸 Machine Learning Project  
## Supervised and Unsupervised Learning using Iris Dataset

---

## 📌 Project Overview

This project demonstrates the implementation of both **Supervised** and **Unsupervised** Machine Learning algorithms using the Iris dataset.

The objective is to understand the complete Machine Learning workflow including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training
- Hyperparameter tuning
- Model evaluation
- Clustering validation
- Comparative analysis

This project showcases structured ML implementation using Python and Scikit-learn.

---

## 📊 Dataset Description

- Dataset: Iris Dataset (Scikit-learn)
- Total Samples: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Classes:
  - Setosa
  - Versicolor
  - Virginica

The dataset:
- Contains no missing values
- Is balanced (50 samples per class)
- Has well-separated feature distributions

---

## 🔬 Technical Approach

### 1️⃣ Data Preprocessing
- Converted dataset into Pandas DataFrame
- Verified data integrity
- Checked for missing values
- Analyzed class distribution
- Applied feature scaling using StandardScaler (important for distance-based models)

### 2️⃣ Exploratory Data Analysis (EDA)
- Pairplot visualization for class separability
- Correlation heatmap
- Feature relationship analysis
- Identified petal length and petal width as strong discriminators

---

## 🔷 Supervised Learning: K-Nearest Neighbors (KNN)

### Steps Performed:
- Train-Test Split (80-20)
- Feature Scaling
- Hyperparameter tuning (K from 1 to 20)
- Optimal K selection
- Final model training
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

### 📈 Results:
- Accuracy: 1.00 (100%)
- Strong class separability
- No misclassifications in test data

---

## 🔶 Unsupervised Learning: K-Means Clustering

### Steps Performed:
- Elbow Method to determine optimal clusters
- Selected K = 3
- Applied K-Means clustering
- Cluster visualization
- Silhouette Score evaluation
- Comparison with actual labels

### 📊 Results:
- Optimal clusters: 3
- Silhouette Score: 0.551
- Clusters closely align with actual species classes

---

## 📊 Model Comparison

| Supervised (KNN) | Unsupervised (K-Means) |
|------------------|------------------------|
| Uses labeled data | No labeled data used |
| Predicts exact class | Discovers natural groups |
| Evaluated using Accuracy | Evaluated using Inertia & Silhouette |
| Higher predictive performance | Good structural grouping |

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## 📅 Project Timeline

Day 1:
- Dataset analysis
- Data preprocessing
- Initial EDA

Day 2:
- KNN implementation
- Hyperparameter tuning
- Model evaluation

Day 3:
- K-Means implementation
- Elbow method
- Silhouette score analysis
- Cluster comparison

Day 4:
- Documentation
- Repository structuring
- Final review and submission

---

## ▶️ How to Run the Project

1️⃣ Clone the repository:
