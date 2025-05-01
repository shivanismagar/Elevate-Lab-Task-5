# Elevate-Lab-Task-5
# Heart Disease Prediction using Decision Trees and Random Forests

## 📌 Objective
To build and evaluate tree-based machine learning models (Decision Tree and Random Forest) to classify whether a person has heart disease based on clinical features.

---

## 🧰 Tools & Libraries
- Python 3
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## 📂 Dataset
**Heart Disease Dataset**

Each row represents a patient and columns are features such as:
- `age`, `sex`, `cp` (chest pain type), `trestbps` (resting blood pressure), `chol` (serum cholesterol), `fbs`, `restecg`, `thalach` (max heart rate), `exang`, `oldpeak`, `slope`, `ca`, `thal`, and
- `target` (0 = no disease, 1 = heart disease)

---

## 🔍 Tasks Performed

### ✅ 1. Data Preprocessing
- Load dataset with `pandas`
- Checked for missing values
- Split data into features (`X`) and label (`y`)

### ✅ 2. Train-Test Split
- Used `train_test_split` from `sklearn` (80% train, 20% test)

### ✅ 3. Decision Tree Classifier
- Trained using `DecisionTreeClassifier`
- Controlled overfitting with `max_depth=4`
- Visualized using `plot_tree`

### ✅ 4. Random Forest Classifier
- Trained using `RandomForestClassifier` with 100 trees
- Compared performance to Decision Tree

### ✅ 5. Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- Cross-validation (`cv=5`) for robustness

### ✅ 6. Feature Importances
- Extracted and visualized most important features from the Random Forest model

---

## 📊 Results Summary

| Model            | Accuracy | Cross-Validation Accuracy |
|------------------|----------|----------------------------|
| Decision Tree    | ~0.82    | ~0.78                      |
| Random Forest    | ~0.88    | ~0.85                      |

*Note: Results may vary slightly depending on split/random state.*

---

## 📈 Visualization Samples
- Decision Tree Plot
- Feature Importance Bar Chart
