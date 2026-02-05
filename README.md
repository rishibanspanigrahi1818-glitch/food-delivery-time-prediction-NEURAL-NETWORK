# 🍔 Food Delivery Time Prediction using Machine Learning

## 📌 Overview
This project focuses on analyzing and predicting food delivery performance using machine learning techniques.  
The goal is to determine whether a food delivery will be **Fast** or **Delayed** based on factors such as distance, traffic conditions, weather, order priority, and other delivery-related attributes.

The project strictly follows the assignment guidelines and demonstrates both **unsupervised learning** and **neural network–based prediction**.

---

## 🎯 Objectives
- Perform data preprocessing and feature engineering on food delivery data
- Identify delivery behavior patterns using clustering techniques
- Predict delivery delays using a neural network model
- Compare different approaches and derive actionable insights

---

## 🗂 Dataset
**File:** `Food_Delivery_Time_Prediction.csv`

### Key Features:
- Customer and Restaurant Location
- Distance
- Weather Conditions
- Traffic Conditions
- Order Priority
- Vehicle Type
- Delivery Time
- Ratings and Cost Information

---

## 🧪 Project Phases

### 🔹 Phase 1: Data Preprocessing & Feature Engineering
- Handling missing values
- Encoding categorical variables
- Feature scaling and normalization
- Distance feature utilization
- Time-based feature engineering (Rush Hour)

---

### 🔹 Phase 2: Clustering Analysis
#### 1️⃣ K-Means Clustering
- Feature selection for clustering
- Elbow Method to determine optimal number of clusters
- Visualization of clusters

#### 2️⃣ Hierarchical Clustering
- Agglomerative clustering
- Dendrogram visualization
- Comparison with K-Means clustering results

---

### 🔹 Phase 3: Neural Network Prediction
- Creation of target variable:
  - **Fast (0)**
  - **Delayed (1)**
- Feature selection for neural network
- Feedforward neural network using Keras/TensorFlow
- Model training and evaluation
- Performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Confusion matrix and training curves

---

### 🔹 Phase 4: Reporting & Insights
- Comparison of clustering insights and neural network performance
- Identification of high-risk delivery patterns
- Business and operational recommendations

---

## 📊 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

## 📈 Key Insights
- High traffic and rush-hour deliveries are more likely to be delayed
- Distance and traffic conditions strongly influence delivery time
- Clustering helps identify delivery behavior patterns
- Neural networks provide effective prediction for delivery delays

---

## 🚀 Recommendations
- Optimize delivery routes for high-risk clusters
- Allocate more delivery resources during peak hours
- Use predictive models to proactively manage delayed orders
- Combine clustering insights with neural network predictions for better decision-making

---

## ✅ Conclusion
This project demonstrates how machine learning can be applied to real-world logistics problems.  
By combining clustering techniques with neural network–based prediction, delivery efficiency and customer satisfaction can be significantly improved.

---

## 📌 Author
**Rishi Bans Panigrahi**

---

## 📜 License
This project is for academic and educational purposes.
