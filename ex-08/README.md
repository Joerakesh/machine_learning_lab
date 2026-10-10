# Exercise 08 — K-Nearest Neighbors (KNN)

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Implement KNN classification for heart disease prediction, compare several K values and select the best-performing K.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and separate the Heart Disease target.
2. Identify numeric and categorical features.
3. Split with stratification.
4. Scale numeric features and one-hot encode categorical features.
5. Train KNN for K=1, 3, 5, 7, 9, 11, 15 and 21.
6. Calculate and plot accuracy, precision, recall and F1 for each K.
7. Evaluate the selected K with confusion matrix, specificity and AUC.

## 4. Implementation
- [Original Python program](./ex-08.py)
- [Jupyter notebook](./ex-08.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The record reports K=11 as best, with accuracy 0.905, precision 0.9155, recall 0.8333, F1 0.8725 and AUC 0.9551.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
