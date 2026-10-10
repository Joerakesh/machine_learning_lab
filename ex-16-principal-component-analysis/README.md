# Exercise 16 — Principal Component Analysis (PCA)

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Apply PCA to reduce the preprocessed heart disease feature space to two components and measure explained variance.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and separate the target.
2. Identify numeric and categorical features.
3. Scale numeric features and one-hot encode categorical features.
4. Convert processed data to a dense array if required.
5. Fit PCA with two components.
6. Transform data and calculate explained variance per component.
7. Plot the two principal components.

## 4. Implementation
- [Original Python program](./ex-16.py)
- [Jupyter notebook](./ex-16.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The 27 processed features were reduced to two components explaining 9.80% and 9.36% of variance respectively, 19.16% total.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check preprocessing, feature scaling, distance/linkage parameters and cluster interpretation as relevant to the method.

## 7. Conclusion

PCA transforms correlated features into orthogonal components ordered by explained variance. The practical record reports that the first two components explain 19.16% of the variance together, so a two-dimensional projection retains only part of the information in the processed dataset. Use the explained-variance ratio to decide whether more components are needed for the intended analysis.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/fish.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`; preserve feature selection, missing-value handling and scaling settings.
