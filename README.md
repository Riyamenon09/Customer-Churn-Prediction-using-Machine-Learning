# 📊 Customer Churn Prediction using Machine Learning
---

## 🚀 Project Highlights

- 📌 Data Cleaning & Preprocessing
- 📊 Exploratory Data Analysis (EDA)
- 🔄 One-Hot Encoding for Categorical Features
- 📏 Feature Scaling using StandardScaler
- 🤖 Model Training using Multiple ML Algorithms
- ⚙️ Hyperparameter Tuning with GridSearchCV
- 📈 Feature Importance Analysis
- 📉 ROC Curve & AUC Comparison
- 📋 Model Performance Comparison

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📂 Dataset Features

- Age
- Gender
- Tenure
- Usage Frequency
- Support Calls
- Payment Delay
- Subscription Type
- Contract Length
- Total Spend
- Last Interaction
- Churn (Target Variable)

---

## 🤖 Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

## ⚙️ Hyperparameter Tuning

GridSearchCV was applied to optimize the Decision Tree, Random Forest, and XGBoost models.

## 📈 Model Performance

| Model | Accuracy | Accuracy After Tuning |
|--------|:--------:|:---------------------:|
| Logistic Regression | **87.98%** | — |
| Decision Tree | **95.04%** | **97.52%** |
| Random Forest | **97.53%** | **97.52%** |
| XGBoost | **97.56%** | **97.50%** |

---

## 📊 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

### AUC Scores

| Model | AUC Score |
|--------|:---------:|
| Decision Tree | **0.985** |
| Random Forest | **0.986** |
| XGBoost | **0.986** |

---

## 📷 Project Visualizations

### Exploratory Data Analysis

- Distribution of Numerical Features
- Customer Churn Distribution by:
  - Gender
  - Subscription Type
  - Contract Length

### Model Evaluation

- Logistic Regression Confusion Matrix
- Decision Tree Confusion Matrix
- Random Forest Confusion Matrix
- XGBoost Confusion Matrix
- Decision Tree Visualization
- Random Forest Feature Importance
- Model Comparison (Before Hyperparameter Tuning)
- ROC Curve Comparison

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Images/
│   ├── distribution_of_numerical_features.png
│   ├── customer_churn_distribution.png
│   ├── logistic_confusion_matrix.png
│   ├── decision_tree_confusion_matrix.png
│   ├── random_forest_confusion_matrix.png
│   ├── xgboost_confusion_matrix.png
│   ├── decision_tree_visualization.png
│   ├── Random_forst_important_features.png
│   ├── model_comaprison_before_tuning.png
│   └── ROC_curve_comparison.png
│
├── Customer_Churn_Prediction.ipynb
├── customer_churn_dataset-training-master.csv
├── README.md

```

---

## 💡 Key Insights

- Developed a complete end-to-end Machine Learning pipeline for customer churn prediction.
- Compared four classification algorithms on the same dataset.
- Applied hyperparameter tuning using GridSearchCV.
- Visualized feature importance to identify key factors influencing customer churn.
- Compared model performance using ROC curves and AUC scores.
- Achieved the highest accuracy of **97.56%** using the XGBoost Classifier.



## 👩‍💻 Author

**Riya S Menon**


