# Exercise 13 — K-Means Clustering

**Course:** Machine Learning Lab  
**Programme:** I M.Sc. Data Science · I Semester  
**Department Number:** 26-PDS-002  
**Student:** Joe Rakesh A · Loyola College, Chennai  
**Academic Year:** 2026–2027

## 1. Aim
Perform K-Means clustering on the heart disease dataset and use the Elbow Method to choose a suitable number of clusters.

## 2. Dataset
- **Expected path:** `heart_disease_dataset.csv`
- Obtain the dataset from an authorised source. Do not commit data that cannot legally be redistributed.
- See the [dataset guide](../datasets/README.md).

## 3. Algorithm / Workflow
1. Load data and remove the Heart Disease target.
2. Scale numeric features and one-hot encode categorical features.
3. Run K-Means for K=1 through 10 and record inertia.
4. Plot the Elbow curve.
5. Fit the final model with selected K.
6. Add cluster labels and count records per cluster.

## 4. Implementation
- [Original Python program](./ex-13.py)
- [Jupyter notebook](./ex-13.ipynb)

The Python program is preserved as-is. The notebook splits its existing code into executable cells; it does not replace the original implementation.

## 5. Results
**Result summary transcribed from the supplied practical record:**

The practical record identifies K=3 as suitable; 1000 records were grouped into clusters of 308, 337 and 355.

This is a recorded result, not a fresh run performed during this update. Run the notebook with the correct dataset and dependencies to generate current outputs and plots.

## 6. Interpretation and validation
Interpret outputs from your run and document limitations. Check preprocessing, feature scaling, distance/linkage parameters and cluster interpretation as relevant to the method.

## 7. Conclusion
Summarise findings from your execution; do not report metrics that were not computed.

## 8. Reproducibility
Record Python version, dataset source/version and dependencies. Run from this exercise directory so relative paths resolve as expected.
