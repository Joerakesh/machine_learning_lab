# Exercise 12 — Hyperparameter Tuning

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Tune an SVM classifier for heart disease prediction using GridSearchCV with cross-validation.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and separate the Heart Disease target.
2. Build a pipeline for numeric scaling, categorical one-hot encoding and SVC.
3. Split 80:20 with stratification.
4. Define grids for C, kernel and gamma.
5. Run GridSearchCV with 5-fold cross-validation and accuracy scoring.
6. Display best parameters and cross-validation score.
7. Evaluate the selected model on the test set.

## 4. Implementation
- [Original Python program](./ex-12.py)
- [Jupyter notebook](./ex-12.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

GridSearchCV selected C=100, kernel=rbf and gamma=auto with cross-validation accuracy 0.9225. Test accuracy was 0.915, precision 0.9067, recall 0.8718 and F1 0.8889.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check for leakage, duplicates and evaluation design before interpreting unexpectedly high classification scores as generalisable.

## 7. Conclusion

GridSearchCV systematically evaluates the specified SVM parameter combinations using cross-validation. The recorded search selected C=100, RBF kernel and gamma=auto. The selected configuration should be judged by held-out test performance, and all preprocessing should be included in a pipeline to avoid leakage during cross-validation.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/heart_disease_dataset.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`, as well as the parameter grid, CV folds and random seed.
