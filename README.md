# 🚗 Logistic Regression on SUV Dataset

## 📌 Project Overview
This project implements a complete Machine Learning pipeline using **Logistic Regression** 
to predict whether a customer will purchase an SUV based on:

- Age  
- Estimated Salary  

The dataset includes:
- Gender (categorical)
- Age
- EstimatedSalary
- Purchased (Target Variable)

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Understanding
- Display first 5 rows
- Check dataset shape and columns
- Check data types
- Identify missing values

### 2️⃣ Data Preprocessing
- Handle missing values
- Encode categorical variable (Gender)
- Select relevant features (Age, EstimatedSalary)
- Separate Features (X) and Target (y)

### 3️⃣ Train-Test Split
- Split dataset into 80% training and 20% testing

### 4️⃣ Feature Scaling
- Apply StandardScaler to normalize feature values

### 5️⃣ Model Training
- Train Logistic Regression model
- Fit model on training data

---

## 📊 Model Evaluation

- Predict on test data
- Compute Accuracy Score
- Generate Confusion Matrix
- Visualize decision boundary (2D plot)

---

## 🔍 Stretch Experiments

- Compare accuracy using:
  - 70/30 split
  - 75/25 split
- Analyze performance differences

---

## 🎯 Interview Questions

### Q1: What is Logistic Regression?
Logistic Regression is a supervised machine learning algorithm used for **binary classification**.  
It uses the **Sigmoid function** to predict probabilities between 0 and 1.

Mathematical Formula:

\[
P(y=1) = \frac{1}{1 + e^{-(b0 + b1x1 + b2x2)}}
\]

---

### Q2: What is a Confusion Matrix?

A Confusion Matrix is a 2×2 table used to evaluate classification performance:

|                | Predicted 0 | Predicted 1 |
|---------------|------------|------------|
| Actual 0      | TN         | FP         |
| Actual 1      | FN         | TP         |

- **TP** → Correctly predicted buyers  
- **TN** → Correctly predicted non-buyers  
- **FP** → Incorrectly predicted buyers  
- **FN** → Missed actual buyers  

It helps calculate:
- Accuracy
- Precision
- Recall
- F1-Score

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Key Learning Outcomes

- End-to-end ML pipeline implementation  
- Importance of Feature Scaling  
- Working of Logistic Regression  
- Model evaluation using confusion matrix  
- Comparing different train-test splits  

---

## 🚀 How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
python main.py
```

---

## 👨‍💻 Author
Vishal Pagadala

---

## 📌 Conclusion

Logistic Regression performs well for linearly separable datasets and serves as a strong baseline model for binary classification problems.
