
# Logistic Regression Classifier: Breast Cancer Diagnosis

This project implements a binary classification model using **Logistic Regression** to predict whether a tumor is malignant or benign, based on the **Breast Cancer Wisconsin Diagnostic Dataset**.

## 📁 Dataset
The dataset is sourced from UCI Machine Learning Repository and contains various features computed from digitized images of a breast mass. The target variable is:
- `M` (Malignant) → 1
- `B` (Benign) → 0

## 🔧 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🧠 Logistic Regression: Key Concepts
- Uses **sigmoid function** to map inputs to probabilities.
- Produces output between 0 and 1 (interpreted as class probabilities).
- Good for **binary classification** tasks.

## 📝 Steps Performed
1. **Data Loading** and preprocessing (drop ID columns, encode target).
2. **Train-Test Split** using `train_test_split`.
3. **Standardization** with `StandardScaler`.
4. **Model Training** with `LogisticRegression`.
5. **Evaluation** using:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC Curve and AUC score
6. **Threshold Tuning** to adjust sensitivity of classification.
7. **Sigmoid Visualization** to explain how Logistic Regression works.

## 📊 Evaluation Metrics
- **Confusion Matrix** for classification performance.
- **ROC-AUC** for measuring model quality across thresholds.
- **Classification Report** (Precision, Recall, F1).

## 📈 Visualization
- ROC Curve showing model performance.
- Sigmoid curve showing logistic transformation.

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python logistic_regression_breast_cancer.py
```

## 📁 File Structure
```
.
├── data.csv                         # Dataset file
├── logistic_regression_breast_cancer.py  # Main code file
└── README.md                        # Project documentation
```

## 📌 Note
Ensure the `data.csv` file is placed in the same directory as the Python script for correct execution.

## 📬 Contact
For queries or contributions, please open an issue or reach out via GitHub.

---
