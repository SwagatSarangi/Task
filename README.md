# Titanic Survival Prediction - Data Science Project

This project develops a machine learning model to predict whether a passenger survived the Titanic disaster. It was completed by **Swagat Sarangi** as part of an  assignment.

## 🚀 Project Objectives

- Preprocess and clean Titanic passenger data
- Handle missing values effectively
- Encode categorical features
- Normalize numerical data
- Perform Exploratory Data Analysis (EDA)
- Train a machine learning classifier (Random Forest)
- Evaluate the model using accuracy, precision, recall, and F1-score
- Visualize key metrics like confusion matrix and feature importances

---

## 🧠 Model Used

**Random Forest Classifier** 

- Robust to overfitting
- Works well with categorical and numerical features
- Provides feature importance directly
- Outperforms a basic decision tree in stability and accuracy

---

## ⚙️ Preprocessing Steps

- Removed irrelevant or sparse columns: `PassengerId`, `Name`, `Ticket`, `Cabin`
- Imputed missing values in `Age` and `Fare` using median
- Label-encoded `Sex` and `Embarked` columns
- Scaled `Age` and `Fare` using `StandardScaler`
- Split data into **80% training / 20% test**

---

## 📊 Exploratory Data Analysis (EDA)

- **Survival Distribution** by count and gender
- **Age Distribution** with KDE (smooth curve)
- **Correlation Heatmap** to examine relationships
- EDA helped validate feature importance and survival patterns

---

## ✅ Model Evaluation

- **Accuracy**: High test accuracy (100% in our example split)
- **Precision**: Correctness of positive predictions
- **Recall**: Ability to identify all true survivors
- **F1 Score**: Balance of precision and recall

### Additional Visuals:

- **Feature Importance Chart**: Which features most affected survival

---



