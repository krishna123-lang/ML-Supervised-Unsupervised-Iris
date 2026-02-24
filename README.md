# 🌸 Machine Learning Project  
## Supervised and Unsupervised Learning using Iris Dataset

---

## 📌 Project Overview

This project demonstrates the implementation of both **Supervised** and **Unsupervised** Machine Learning algorithms using the Iris dataset.

The objective of this project is to understand and implement the complete Machine Learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training
- Hyperparameter tuning
- Model evaluation
- Clustering validation
- Comparative analysis

This project reflects structured problem-solving and practical implementation of core ML concepts.

---

## 📊 Dataset Description

- Dataset: Iris Dataset (from Scikit-learn)
- Total Samples: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target Classes:
  - Setosa
  - Versicolor
  - Virginica

### Dataset Characteristics:
- No missing values
- Balanced dataset (50 samples per class)
- Well-separated feature distributions
- Petal features show strong correlation with target class

---

## 🔬 Technical Approach

### 1️⃣ Data Preprocessing
- Loaded dataset using Scikit-learn
- Converted to Pandas DataFrame
- Verified data integrity
- Checked for missing values
- Analyzed class distribution
- Applied feature scaling using StandardScaler (important for distance-based models like KNN)

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Generated pairplot visualization
- Created correlation heatmap
- Analyzed feature relationships
- Identified petal length and petal width as strong discriminators

---

## 🔷 Supervised Learning: K-Nearest Neighbors (KNN)

### Steps Performed:
- Train-Test Split (80% training, 20% testing)
- Feature Scaling
- Hyperparameter tuning (K values from 1 to 20)
- Optimal K selection based on minimum error rate
- Final model training
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

### 📈 Results:
- Accuracy: 1.00 (100%)
- Clear class separation
- No misclassifications in test dataset

### Key Insight:
Feature scaling significantly improved performance due to the distance-based nature of KNN.

---

## 🔶 Unsupervised Learning: K-Means Clustering

### Steps Performed:
- Used Elbow Method to determine optimal number of clusters
- Selected K = 3
- Applied K-Means clustering
- Visualized clusters
- Calculated Silhouette Score
- Compared clusters with actual class labels

### 📊 Results:
- Optimal Clusters: 3
- Silhouette Score: 0.551
- Clusters closely align with actual species labels

### Key Insight:
Although clustering is unsupervised, K-Means successfully identified meaningful natural groupings in the dataset.

---

## 📊 Supervised vs Unsupervised Comparison

| Supervised (KNN) | Unsupervised (K-Means) |
|------------------|------------------------|
| Uses labeled data | No labeled data |
| Predicts exact species | Finds natural groupings |
| Evaluated using Accuracy | Evaluated using Inertia & Silhouette Score |
| Higher predictive performance | Meaningful structural grouping |

---

## 🛠️ Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab
- Git & GitHub

---

## ▶️ How to Run the Project

### 🔹 Option 1: Open Directly in Google Colab

Click below to run instantly:

[Open in Google Colab](https://colab.research.google.com/github/krishna123-lang/ML-Supervised-Unsupervised-Iris/blob/main/ML_Project_Iris.ipynb)

---

### 🔹 Option 2: Run Locally

1️⃣ Clone the repository:
