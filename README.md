# Heart_Disease_Dataset

# Decision Trees and Random Forests 

## 🎯 Objective

This project demonstrates the use of tree-based models — Decision Tree and Random Forest — for classifying heart disease using the `heart.csv` dataset.

---

## 🧰 Tools Used

- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **NumPy**

---

## 📊 Dataset

- **File:** `heart.csv`
- **Target column:** `target` (0 = No Heart Disease, 1 = Heart Disease)
- **Features include:** Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), Fasting Blood Sugar (fbs), Max Heart Rate (thalach), etc.

---

## 🛠️ Tasks Performed

### 1. Data Loading and Splitting
- Loaded the CSV file using `pandas`.
- Split data into features (X) and target (y).
- Performed train/test split.

### 2. Decision Tree Classifier
- Trained a full-depth Decision Tree.
- Visualized the tree using `plot_tree`.

### 3. Overfitting Control
- Re-trained the Decision Tree using `max_depth=4`.
- Compared training and testing accuracy.

### 4. Random Forest Classifier
- Trained a `RandomForestClassifier` with 100 trees.
- Compared performance with the Decision Tree.

### 5. Feature Importance
- Extracted and visualized feature importances from the Random Forest model.

### 6. Cross-Validation
- Performed 5-fold cross-validation on the Random Forest model.
- Reported mean accuracy.

---

## 📈 Results Summary

| Model              | Train Accuracy | Test Accuracy |
|-------------------|----------------|---------------|
| Decision Tree      | High (overfitting likely) | Lower than training |
| Decision Tree (pruned) | Balanced | Improved generalization |
| Random Forest      | High (but more generalized) | Better than pruned tree |

---

