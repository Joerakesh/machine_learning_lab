# Exercise 09 — Decision Tree

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Build a Decision Tree classifier for heart disease prediction and evaluate and visualise the trained model.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and separate the Heart Disease target.
2. Identify numeric and categorical columns.
3. Preprocess numeric features with scaling and categorical features with one-hot encoding.
4. Split 80:20 with stratification.
5. Train DecisionTreeClassifier(max_depth=4).
6. Calculate accuracy, precision, recall, F1, classification report and confusion matrix.
7. Visualise the confusion matrix and trained tree.

## 4. Implementation
- [Original Python program](./ex-09.py)
- [Jupyter notebook](./ex-09.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The practical record reports accuracy, precision, recall and F1 of 1.0 on 200 test records, with 122 true negatives and 78 true positives. Perfect scores warrant checks for leakage and split integrity.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion

A Decision Tree learns rule-based splits for classification and can be visualised for interpretation. The practical record reports perfect test metrics, which should be treated cautiously until target construction, duplicate rows, preprocessing, train/test separation and possible leakage are checked. Perfect scores do not by themselves demonstrate generalisation.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/heart_disease_dataset.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`; verify the split and preprocessing for leakage.
