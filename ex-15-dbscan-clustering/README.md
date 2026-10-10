# Exercise 15 — DBSCAN Clustering

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Perform DBSCAN clustering on the heart disease dataset, identify clusters and noise points, and visualise the result using PCA.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and separate the target.
2. Identify numeric and categorical features.
3. Scale numeric features and one-hot encode categorical features.
4. Apply DBSCAN(eps=1.5, min_samples=5).
5. Assign cluster labels and count clusters/noise.
6. Apply PCA to two dimensions and plot the clustering result.

## 4. Implementation
- [Original Python program](./ex-15.py)
- [Jupyter notebook](./ex-15.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

With eps=1.5 and min_samples=5, the practical record reports all 1000 records as noise and no clusters in the 27-dimensional feature space.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check preprocessing, feature scaling, distance/linkage parameters and cluster interpretation as relevant to the method.

## 7. Conclusion
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
