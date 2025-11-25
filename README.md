# ❤️ Heart Attack Prediction Using Machine Learning

## 📌 Project Overview
This project uses machine learning techniques to predict the likelihood of a heart attack based on key medical features. It covers the complete ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. The goal is to build a reliable model that can help in early detection and medical decision support.

---

## 📊 Dataset Description
The dataset contains essential cardiovascular health indicators:

- **Age**
- **Sex**
- **Chest Pain Type (cp)**
- **Resting Blood Pressure (trtbps)**
- **Cholesterol (chol)**
- **Fasting Blood Sugar (fbs)**
- **Resting ECG (restecg)**
- **Maximum Heart Rate (thalachh)**
- **Exercise-Induced Angina (exng)**
- **ST Depression (oldpeak)**
- **Slope (slp)**
- **Number of Major Vessels (caa)**
- **Thalassemia (thall)**
- **Output (1 = heart attack risk, 0 = low risk)**

These features help identify patterns and risk levels associated with cardiovascular disease.

---

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values  
- Encoding categorical features  
- Scaling numerical variables  
- Outlier detection and removal  

### 2️⃣ Exploratory Data Analysis (EDA)
- Correlation heatmap  
- Feature distributions  
- Risk pattern analysis  
- Identifying top contributing factors  

### 3️⃣ Model Development
The following machine learning models were trained and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  

### 4️⃣ Model Evaluation
Models were evaluated using:

- **Accuracy**
- **Precision, Recall, F1-score**
- **Confusion Matrix**
- **ROC–AUC Curve**

The best-performing model showed strong and balanced performance across all metrics.

---

## 🧠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run the Project

### Install Dependencies
```bash
pip install -r requirements.txt
