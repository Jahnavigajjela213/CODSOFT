# 📧 Task 1 - Spam SMS Detection

## 🎯 Objective
To develop a machine learning model that can accurately classify SMS messages as either **spam** or **ham** (legitimate). This task demonstrates the use of Natural Language Processing (NLP) and supervised learning techniques.


## 📁 Dataset
- **Source**: [UCI SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Shape**: `(5572, 2)`
- The dataset contains over 5,500 SMS messages labeled as "spam" or "ham".

### 📌 Sample Data

 Label - Message 

 ham   - Go until jurong point, crazy.. Available only ... 
 ham   - Ok lar... Joking wif u oni... 
 spam  - Free entry in 2 a wkly comp to win FA Cup fina...
 ham   - U dun say so early hor... U c already then say... 
 ham   - Nah I don't think he goes to usf, he lives aro... 


## 🛠️ Technologies Used
- Python
- pandas, NumPy
- scikit-learn
- Matplotlib & Seaborn
- TF-IDF Vectorization
- Logistic Regression Classifier


## 📌 Project Workflow

1. **Data Loading** – Loaded the dataset from UCI's GitHub
2. **Exploratory Data Analysis** – Checked label distribution
3. **Preprocessing** – Mapped labels to binary, cleaned data
4. **Text Vectorization** – Used TF-IDF to convert text to numeric vectors
5. **Model Building** – Trained a Logistic Regression classifier
6. **Model Evaluation** – Assessed accuracy, classification report, and confusion matrix
7. **Visualization** – Plotted label distribution and confusion matrix
8. **Prediction** – Tested with a custom message for spam detection


## 📊 Visual Output

### ✅ Distribution of Spam and Ham

Dataset shape: (5572, 2)

Sample data:
   Label                                            Message
0   ham  Go until jurong point, crazy.. Available only ...
1   ham                      Ok lar... Joking wif u oni...
2  spam  Free entry in 2 a wkly comp to win FA Cup fina...
3   ham  U dun say so early hor... U c already then say...
4   ham  Nah I don't think he goes to usf, he lives aro...

<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/ee07f802-4ca6-4b8d-8d47-5ce84d0783b1" />
![Spam Distribution](./494f0157-afce-4e4f-bb72-da2f4089984f.png)

### ✅ Confusion Matrix

✅ Classification Report:

              precision    recall  f1-score   support

           0       0.96      1.00      0.98      1207
           1       1.00      0.76      0.86       186

    accuracy                           0.97      1393
   macro avg       0.98      0.88      0.92      1393
weighted avg       0.97      0.97      0.97      1393

✅ Accuracy Score: 0.9676956209619526

<img width="548" height="455" alt="image" src="https://github.com/user-attachments/assets/f4a1d03d-64ca-4d5a-aa08-97960d77b702" />
![Confusion Matrix](./d25ac558-638c-4142-9381-da098ebc769e.png)


## 📽️ Demo Video
🎥 Watch Demo - https://www.loom.com/share/34cf1e37a47042fd9723eafa2570c918?sid=6e22feb2-da0c-4baa-a229-8d2564bcf92b


## 🔗 GitHub Repository
🔗 https://github.com/Jahnavigajjela213/CODSOFT


## 🏷️ Hashtags
`#codsoft` `#machinelearning` `#internship` `#nlp` `#python`
