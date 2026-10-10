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

DBSCAN identifies dense regions and marks points outside them as noise. The practical record reports that eps=1.5 and min_samples=5 classified all 1,000 records as noise, meaning those settings did not identify clusters in the processed feature space. Investigate feature scaling and the distance distribution, then tune parameters using domain context rather than assuming that no clusters exist.

## 8. Reproducibility

The GitHub Actions workflow uses Python 3.12. The notebook reads `datasets/fish.csv` from this repository's `main` branch. Dependencies are listed in `requirements.txt` without pinned versions. Record the repository commit or dataset checksum, `python --version`, and `python -m pip freeze`; preserve feature selection, scaling, eps and min_samples.
