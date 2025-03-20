# **K-Nearest Neighbors (KNN) Classification**
## **Overview**
This repository contains a Jupyter Notebook implementing **K-Nearest Neighbors (KNN) Classification** to analyze and predict user behavior based on **social network ad interactions**. The dataset used is **`social_network_ads.csv`**.

## **Dataset**
- **`social_network_ads.csv`** contains user demographic information such as:
  - Age
  - Estimated Salary
  - Purchased (Target Variable: Whether the user purchased the product or not)
- The goal is to classify whether a user **purchases a product** based on age and estimated salary using **KNN**.

## **Key Features**
### **Data Preprocessing**
- Load and clean the dataset using `pandas`
- Handle missing values if any
- Standardize features using `StandardScaler`
- Split the dataset into training and test sets using `train_test_split`

### **Model Implementation**
- Train a **K-Nearest Neighbors (KNN) classifier** using `sklearn.neighbors.KNeighborsClassifier`
- Tune the value of **k (number of neighbors)**
- Evaluate the model performance using:
  - **Confusion Matrix**
  - **Classification Report**
  - **Accuracy Score**

### **Visualization**
- Decision boundary visualization of KNN classification
- Distribution of features before and after scaling

## **Results & Insights**
- The trained **KNN model** predicts whether a user will purchase a product based on age and estimated salary.
- Model accuracy and evaluation metrics (precision, recall, F1-score) are displayed.
- Decision boundary visualization helps understand KNN classification performance.

## **Author**
**Chukwuka Onyeka**
