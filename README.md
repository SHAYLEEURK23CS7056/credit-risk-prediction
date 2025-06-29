# Credit Risk Prediction Using Machine Learning

This project aims to predict whether a customer is a **good or bad credit risk** using historical financial and demographic data. It is built as part of a Data Science minor project using classification models.

---

## 📁 Dataset

- **Name:** cs-training.csv  
- **Source:** kaggle**
- **Target Variable:** `SeriousDlqin2yrs`  
  - 0 = Good Credit Risk  
  - 1 = Bad Credit Risk  

---

## 🧠 Objective

To build a classification model that helps financial institutions identify customers who are likely to default on loans based on their profile.

---

## 🧰 Tech Stack

- **Language:** Python  
- **Environment:** Google Colab  
- **Libraries Used:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn (RandomForestClassifier, metrics, train_test_split)

---

## 🔄 Workflow

1. Load and explore the dataset
2. Clean data (missing values, data types, ID column removal)
3. Split into training and testing sets
4. Train model using **Random Forest Classifier**
5. Evaluate performance using accuracy, F1-score, and confusion matrix
6. Visualize with a confusion matrix heatmap

---

## 📊 Model Performance

- **Accuracy:** 93.6%
- **F1-Score (Class 0):** 97%  
- **F1-Score (Class 1):** 28%  

The model performs well in detecting non-defaulters. To improve the detection of defaulters (Class 1), techniques like SMOTE or XGBoost can be used in future iterations.

---

## 📌 Project Files

| File | Description |
|------|-------------|
| `credit-risk-prediction.ipynb` | Main notebook with code and output |
| `cs-training.csv` | Dataset used for training |
| `confusion_matrix.png` | Optional heatmap visualization |
| `README.md` | Project documentation |

---

## ✅ Conclusion

This machine learning model is effective at predicting good credit risk but requires enhancements to better capture high-risk customers. It serves as a strong foundation for credit scoring systems in the finance domain.

