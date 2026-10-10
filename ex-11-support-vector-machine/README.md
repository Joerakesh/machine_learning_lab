# Exercise 11 — Support Vector Machine (SVM)

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Perform SVM classification using Linear, Polynomial, RBF and Sigmoid kernels and compare their performance.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and separate the Heart Disease target.
2. Identify numeric and categorical features.
3. Scale numeric features and one-hot encode categorical features.
4. Split 80:20 with stratification.
5. Train SVM models with all four kernels.
6. Calculate accuracy, precision, recall and F1 for each.
7. Compare results in a table and bar plot.

## 4. Implementation
- [Original Python program](./ex-11.py)
- [Jupyter notebook](./ex-11.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The polynomial kernel performed best with accuracy 0.925 and F1 0.9007, followed by RBF (accuracy 0.905), linear (0.875) and sigmoid (0.825).

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
