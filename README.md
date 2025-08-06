# 🧠 CodSoft Machine Learning Internship Projects

This repository contains all three tasks completed as part of the **CodSoft Machine Learning Internship**, demonstrating practical applications of machine learning concepts. Each task includes code, analysis, results, and visuals.

---

## 📅 Table of Contents

* 📁 Repository Structure :
* [📌 Task 1: Spam SMS Detection](#-task-1-spam-sms-detection)
* [📌 Task 2: Customer Segmentation](#-task-2-customer-segmentation)
* [📌 Task 3: Customer Churn Prediction](#-task-3-customer-churn-prediction)
* [📈 Results Summary](#-results-summary)
* [📼 Demo Video Links](#-demo-video-links)
* [🛠️ Technologies Used](#%EF%B8%8F-technologies-used)

---

## 📌 Task 1: Spam SMS Detection

### ✅ Objective

Build a classifier to detect spam messages using NLP and machine learning.

### 📊 Dataset

* **Dataset**: SMS Spam Collection
* **Columns**: Label (spam/ham), Message

### 🔍 Process

* Data Cleaning
* Text Preprocessing (Lowercasing, Stopword Removal)
* Feature Extraction using CountVectorizer
* Model Training using Naive Bayes

### 🔄 Output

* **Accuracy**: 98%
  
* **Classification Report**:

```
              precision    recall  f1-score   support

         ham       0.99      1.00      0.99       965
        spam       0.97      0.88      0.92       150

    accuracy                           0.98      1115
```
<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/3839b89a-b83a-460d-9542-9add860f65b1" />

Confusion Matrix : <img width="548" height="455" alt="image" src="https://github.com/user-attachments/assets/6eba3320-8e97-4bd5-a460-c15649003bea" />


---

## 📌 Task 2: Credit Card Fraud Detection

### ✅ Objective

To detect fraudulent credit card transactions using supervised learning on a highly imbalanced dataset. The task focuses on real-world fraud detection, evaluating models using accuracy and classification metrics.

### 📊 Dataset

* Source: Kaggle - Credit Card Fraud Detection
* Total Transactions: 284,807
* Fraudulent Transactions: 492 (Class 1)
* Legitimate Transactions: 284,315 (Class 0)

### 🔍 Process

* EDA
* Feature Scaling
* Balancing Classes

### 🔄 Output

✅ Accuracy Score: 0.9995
✅ Classification Report:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     85295
           1       0.96      0.76      0.85       148

    accuracy                           1.00     85443
   macro avg       0.98      0.88      0.92     85443
weighted avg       1.00      1.00      1.00     85443

<img width="566" height="393" alt="image" src="https://github.com/user-attachments/assets/a170c582-d144-46e3-813c-4cc490b6eb25" />

Confusion Matrix : <img width="527" height="393" alt="image" src="https://github.com/user-attachments/assets/19ca3d2c-bb17-4238-a803-5c49a76b57d2" />


---

## 📌 Task 3: Customer Churn Prediction

### ✅ Objective

Predict whether a bank customer will leave the service (churn) or stay.

### 📊 Dataset

* **Dataset**: Churn\_Modelling.csv
* **Target**: Exited (1=Churned, 0=Stayed)

### 🔍 Process

* Data Cleaning & Preprocessing
* One-hot Encoding for categorical features
* Feature Selection
* Model Training using Logistic Regression

### 🔄 Output

* **Accuracy**: 87%
* **Classification Report**:

```
              precision    recall  f1-score   support

           0       0.88      0.97      0.92      1593
           1       0.79      0.49      0.60       407

    accuracy                           0.87      2000
```

<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/96de81f7-5da4-4c79-8f1d-a35d5f111c72" />

Confusion Matrix : <img width="548" height="455" alt="image" src="https://github.com/user-attachments/assets/3d51271f-dfa7-41e4-aa3f-bbf92baed209" />


---

## 📼 Demo Video Links

* **Task 1**: (https://www.loom.com/share/34cf1e37a47042fd9723eafa2570c918?sid=b3720b89-b232-43af-be30-de19438ec1bc)
* **Task 2**: (https://www.loom.com/share/40711d1e807a41f5b798499985169409?sid=6ff6f744-f848-4f22-a918-94594c470244)
* **Task 3**: (https://www.loom.com/share/c38d1c1adf6641c386302cfc82072900?sid=2640364e-66b8-4c21-9099-56d4737d7cd4)
---

## 📈 Results Summary

| Task                            | Model Used          | Accuracy        |
| ------------------------------- | ------------------- | --------------- |
| Spam SMS Detection              | Naive Bayes         | 98%             |
| Credit Card Fraud Detection     | Logistic Regression | 99.5%           |
| Customer Churn Prediction       | Gradient Boosting   | 87%             |

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Seaborn & Matplotlib
* Jupyter Notebook
* Loom (for video demos)

---

### 🚀 Author

**Jahnavi Gajjela**
*Machine Learning Intern at CodSoft*
