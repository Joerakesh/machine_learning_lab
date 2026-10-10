# Exercise 10 — Random Forest

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Build and evaluate a Random Forest classifier for heart disease prediction, including ROC-AUC analysis.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load and inspect the dataset, missing values and target distribution.
2. Separate features from the Heart Disease target.
3. Prepare preprocessing for numeric and categorical features.
4. Create RandomForestClassifier(n_estimators=100, random_state=42).
5. Split data, train and predict.
6. Calculate train/test accuracy, precision, recall and F1.
7. Plot ROC and calculate ROC-AUC.

## 4. Implementation
- [Original Python program](./ex-10.py)
- [Jupyter notebook](./ex-10.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The practical record reports training accuracy 1.0, test accuracy 0.99, precision 1.0, recall 0.9744, F1 0.987 and ROC-AUC 1.0.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
