# Decision-Trees-and-Random-Forests
Decision Trees and Random Forests

## 🎯 Objective

This task focuses on understanding and applying **tree-based models** for classification. We build, visualize, and evaluate both a **Decision Tree** and a **Random Forest** using the Breast Cancer dataset.

---

## 🧰 Tools & Libraries Used

- Python 3.x
- Scikit-learn
- Graphviz (for tree visualization)
- Pandas, NumPy
- Seaborn, Matplotlib

---

## 📁 Dataset

- **Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **Source:** Built-in with `sklearn.datasets`
- **Target:** Binary classification (Malignant vs Benign)
- **Features:** 30 numerical predictors related to tumor measurements

---

## ✅ Tasks Completed

### 1. Train a Decision Tree
- Used `DecisionTreeClassifier` with `max_depth=3` to control overfitting.
- Visualized the decision tree using `plot_tree`.

### 2. Overfitting Control
- Used `max_depth`, `min_samples_split` to prevent deep trees.
- Observed how shallow trees generalize better.

### 3. Train and Compare Random Forest
- Trained a `RandomForestClassifier` with 100 trees.
- Compared accuracy and classification metrics with the decision tree.

### 4. Feature Importances
- Extracted and visualized the most important features used by the Random Forest.

### 5. Cross-Validation
- Performed 5-fold cross-validation to compare model robustness.
- Found that **Random Forest generally outperformed** the single decision tree.

---

## 🧪 Results

| Metric                      | Decision Tree | Random Forest |
|----------------------------|----------------|----------------|
| Accuracy (Test Set)        | ~92%           | ~96%           |
| Cross-Validation Accuracy  | ~92%           | ~97%           |
| Top Feature                | worst perimeter | worst concave points |

---

## 🧠 Key Learnings

- **Decision Trees** are interpretable but prone to overfitting if not pruned.
- **Random Forests** improve accuracy by reducing variance through ensemble learning.
- **Feature Importance** helps identify key drivers of prediction.
- Cross-validation provides a more reliable estimate of model performance.

---

## 🖼️ Tree Visualization

- The Decision Tree is visualized using `matplotlib.pyplot` and `plot_tree`.
- For more complex visualizations, Graphviz can be integrated.

---



