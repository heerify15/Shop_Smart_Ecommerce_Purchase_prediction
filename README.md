# 🛒 ShopSmart E-commerce Purchase Prediction

## 📌 Overview

This project aims to predict whether a visitor to an e-commerce website will complete a purchase based on their browsing behaviour during a session. The project demonstrates an end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, hyperparameter tuning, and evaluation.

---

## 🎯 Objective

Develop a Decision Tree Classification model capable of predicting customer purchase intent while effectively handling an imbalanced dataset. The model is optimized using pruning techniques and hyperparameter tuning to improve generalization performance.

---

## 🚀 Project Workflow

- Data Loading & Exploration
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Handling Boolean Features
- Feature Scaling using `StandardScaler`
- Encoding Categorical Features using `OneHotEncoder`
- Building a preprocessing pipeline using `ColumnTransformer`
- Training a Decision Tree Classifier
- Cost Complexity Pruning
- Hyperparameter Tuning using `GridSearchCV`
- Model Evaluation

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Model Evaluation

The model is evaluated using multiple classification metrics, with a primary focus on the **F1 Score** due to the class imbalance.

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📂 Repository Structure

```
ShopSmart-Ecommerce-Purchase-Prediction/
│
├── Dataset/
│   └── shop_smart_ecommerce.csv
│
├── Notebook/
│   └── ShopSmart_Ecommerce_Purchase_Prediction.ipynb
│
├── Output/
│   ├── EDA Visualizations
│   ├── Confusion Matrix
│   ├── Decision Tree
│   ├── Feature Importance
│   └── Model Evaluation Results
│
├── Dataset Description.pdf
├── Problem Statement.pdf
├── README.md
└── LICENSE
```

---

## 📌 Key Learning Outcomes

- Performed comprehensive Exploratory Data Analysis (EDA)
- Built an end-to-end preprocessing pipeline
- Applied feature scaling and categorical encoding
- Trained and optimized a Decision Tree Classifier
- Improved model performance using Cost Complexity Pruning
- Tuned hyperparameters using GridSearchCV
- Evaluated the model using appropriate classification metrics for imbalanced data

---

## 🔮 Future Improvements

- Random Forest Classifier
- AdaBoost Classifier
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost
- Model Deployment using Streamlit or Flask

---

## 👩‍💻 Author

**Heer Shah**

Computer Science (AI & Machine Learning) Student

---

⭐ If you found this project helpful, feel free to star the repository!
