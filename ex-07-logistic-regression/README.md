# Exercise 07 — Logistic Regression

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Implement Logistic Regression for binary heart disease classification and evaluate it using classification metrics and ROC-AUC.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load the heart disease data and separate the Heart Disease target.
2. Identify numeric and categorical columns; impute missing values with the most frequent value.
3. Encode categorical columns.
4. Split 80:20 with random_state=42.
5. Train LogisticRegression(max_iter=1000).
6. Calculate accuracy, precision, recall and F1.
7. Display the confusion matrix and classification report.
8. Plot the ROC curve and calculate ROC-AUC.

## 4. Implementation
- [Original Python program](./ex-07.py)
- [Jupyter notebook](./ex-07.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The record reports accuracy 86.5%, precision 0.8493, recall 0.7949, F1 0.8212 and ROC-AUC 0.9505 on the test set.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion

Logistic Regression provides a baseline for binary heart-disease classification. The recorded precision, recall, F1 and ROC-AUC describe different aspects of performance and should be considered together; the results are not proof of clinical usefulness and require validation on representative, independent data.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/heart_disease_dataset.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`. Check preprocessing is fitted only on training data.
