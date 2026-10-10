# Exercise 14 — Hierarchical Clustering

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Perform hierarchical clustering on preprocessed heart disease data using Ward linkage and visualise the hierarchy with a dendrogram.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and remove the Heart Disease target.
2. Identify numeric and categorical features.
3. Standardise numeric features and one-hot encode categorical features.
4. Convert processed data to a dense array.
5. Apply Ward linkage hierarchical clustering.
6. Plot a truncated dendrogram showing the last 30 merges.

## 4. Implementation
- [Original Python program](./ex-14.py)
- [Jupyter notebook](./ex-14.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

Ward linkage was applied to 1000 records with 27 processed features. The dendrogram illustrates how records merge into larger clusters.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check preprocessing, feature scaling, distance/linkage parameters and cluster interpretation as relevant to the method.

## 7. Conclusion

Agglomerative hierarchical clustering builds nested groups, and the dendrogram shows the order and distance at which clusters merge. The recorded experiment used Ward linkage on 1,000 records and 27 processed features. The number of meaningful clusters depends on where the dendrogram is cut and on feature preprocessing and scaling.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/fish.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`; preserve selected features, preprocessing and linkage settings.
