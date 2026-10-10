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

The experiment compares SVM kernels and the practical-record results favour the polynomial kernel on the reported test split. Kernel performance can change with scaling, hyperparameters and data splits, so compare results using the same validation procedure and keep the final test set separate from model selection.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/heart_disease_dataset.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`; preserve split, scaling and kernel settings.
