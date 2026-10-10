# Exercise 06 — Lasso Regression

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Implement Lasso Regression (L1 regularisation) on the housing dataset using fourth-degree polynomial features and compare it with ordinary linear regression.

## 2. Dataset
- **Expected path:** `Dataset/Housing.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load Housing.csv and create dummy variables.
2. Split into train/test sets (80:20, random_state=42).
3. Standardise features.
4. Generate degree-4 polynomial features.
5. Fit ordinary LinearRegression and record train/test R².
6. Fit Lasso(alpha=0.1, max_iter=50000).
7. Compare model scores and train/test gaps in a table and bar chart.

## 4. Implementation
- [Original Python program](./ex-06.py)
- [Jupyter notebook](./ex-06.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The record reports ordinary linear regression train R² 0.9940 and test R² −2874.77. Lasso(alpha=0.1) had train R² 0.9922 and test R² −13.50. Overfitting was reduced, although test R² remained negative.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
