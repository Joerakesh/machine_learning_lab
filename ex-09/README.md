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
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
