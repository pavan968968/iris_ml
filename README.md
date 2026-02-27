# Iris Dataset Analysis using Supervised and Unsupervised Learning

## 📌 Project Overview

This project demonstrates the application of both supervised and unsupervised machine learning algorithms on the Iris dataset. The objective is to perform classification using K-Nearest Neighbors (KNN) and clustering using K-Means, along with data preprocessing and visualization.

This project was completed as part of an internship submission to demonstrate understanding of core machine learning concepts.

---

## 📊 Dataset

- Dataset: Iris Dataset (from scikit-learn)
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

---

## 🧠 Algorithms Used

### 1️⃣ Supervised Learning
**K-Nearest Neighbors (KNN)**  
- Used for classification  
- Applied train-test split  
- Feature scaling performed  
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report  

### 2️⃣ Unsupervised Learning
**K-Means Clustering**  
- Applied with 3 clusters  
- Evaluated using:
  - Inertia
  - Silhouette Score  
- PCA used for 2D visualization  

---

## 🔧 Implementation Steps

1. Data loading using scikit-learn
2. Train-test split (80-20)
3. Feature scaling using StandardScaler
4. Model training
5. Performance evaluation
6. Cluster visualization using PCA and Matplotlib

---

## 📈 Results

- KNN achieved high classification accuracy on the test set.
- K-Means successfully identified natural groupings in the dataset.
- PCA visualization clearly showed separation between clusters.

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📂 Repository Structure
 

---

## 🎯 Conclusion

This project demonstrates fundamental understanding of:

- Supervised vs Unsupervised Learning
- Data preprocessing techniques
- Model training and evaluation
- Visualization of clustering results

The implementation highlights practical application of machine learning algorithms on structured datasets.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Comparison with other algorithms
- Deployment as a simple web application