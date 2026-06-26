# Customer_churn_prediction

# 🏦 Bank Customer Churn Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project focuses on predicting whether a bank customer is likely to leave the bank (Customer Churn Prediction) using an Artificial Neural Network (ANN). Since the dataset contained an imbalanced target variable, multiple imbalance handling techniques were implemented and compared to improve the model's performance.

The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, handling of imbalanced classes, and ANN model development using TensorFlow/Keras.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) to understand customer behavior.
- Analyze the relationship between customer attributes and churn.
- Handle class imbalance using multiple techniques.
- Build an Artificial Neural Network (ANN) for binary classification.
- Compare model performance before and after balancing the dataset.

---

## 📊 Exploratory Data Analysis

EDA was performed to gain insights into customer behavior and important features affecting churn.

Some of the analyses include:

- Customer churn distribution
- Credit Score vs Churn
- Estimated Salary vs Churn
- Age distribution
- Balance distribution
- Correlation analysis
- Feature visualization using histograms, count plots, and heatmaps

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Label Encoding
- One-Hot Encoding
- Feature Scaling (Min-Max Scaling)
- Train-Test Split

---

## 🧠 Artificial Neural Network

The ANN was implemented using **TensorFlow/Keras**.

### Model Architecture

- Input Layer
- Hidden Layer (ReLU Activation)
- Hidden Layer (ReLU Activation)
- Output Layer (Sigmoid Activation)

### Loss Function

- Binary Crossentropy

### Optimizer

- Adam

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## ⚖️ Handling Imbalanced Dataset

The dataset contained an imbalanced target variable.

Three different techniques were implemented and compared:

### 1. Random Undersampling
Reduced the majority class to balance the dataset.

### 2. Random Oversampling
Increased the minority class by randomly duplicating samples.

### 3. SMOTE (Synthetic Minority Over-sampling Technique)
Generated synthetic samples for the minority class to create a balanced dataset.

The performance of the ANN was evaluated after applying each technique.

---

## 📈 Results

The ANN model was trained on:

- Original Dataset
- Undersampled Dataset
- Oversampled Dataset
- SMOTE Balanced Dataset

The model showed improved classification performance after handling class imbalance. Among the balancing techniques, model performance (accuracy and classification metrics) improved progressively, demonstrating the importance of addressing imbalanced datasets in classification problems.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Imbalanced-learn (SMOTE)

---

## 📂 Project Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Encoding
6. Feature Scaling
7. Train-Test Split
8. Handle Imbalanced Dataset
   - Undersampling
   - Oversampling
   - SMOTE
9. Build ANN Model
10. Train & Evaluate Model
11. Compare Results

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Early Stopping
- Dropout Layers
- Model Deployment using Flask/FastAPI
- Explainable AI using SHAP or LIME

---

## 📜 Conclusion

This project demonstrates how Artificial Neural Networks can effectively predict customer churn in the banking sector. It also highlights the significant impact of handling imbalanced datasets using techniques such as Random Undersampling, Random Oversampling, and SMOTE. Comparing these approaches shows that balancing the data can improve the model's ability to identify churning customers and produce more reliable predictions.

---

⭐ If you found this project useful, feel free to star the repository.
