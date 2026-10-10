<div align="center">

<img src="https://eatright.loyolacollege.edu/_app/immutable/assets/loyola-logo.C2NjGpy4.webp" alt="Loyola College logo" width="130" />

# LOYOLA COLLEGE, CHENNAI
### Department of Data Science

# Machine Learning Laboratory
**M.Sc. Data Science · I Semester · Academic Year 2026–2027**

**Practical Record & Code Portfolio**

</div>

---

## Student Details

| Field | Details |
|---|---|
| **Name** | Joe Rakesh A |
| **Department Number (D.No.)** | **26-PDS-002** |
| **Programme / Class** | I M.Sc. Data Science |
| **Semester** | I Semester |
| **Course Title** | Machine Learning Lab |
| **Institution** | Loyola College, Chennai – 600 034 |
| **Academic Year** | 2026–2027 |

> This repository accompanies the Machine Learning Lab practical record for the Department of Data Science. The exercise titles, aims, algorithms and reported results are based on the supplied practical record. The Python scripts are preserved as the original implementations.

## About this repository

This repository contains 16 machine learning laboratory exercises, organised by experiment number. Each exercise includes a standalone Python program, a detailed README, and a Jupyter notebook for interactive execution and exploration.

The notebooks are designed to display code, tables, charts and output when run in an environment with the required datasets and libraries. Recorded result summaries below are transcribed from the practical record; they are not claims that every notebook was freshly executed by GitHub.

## Exercise Index

| Ex. No. | Experiment | Main concepts | Python | Notebook |
|---:|---|---|---|---|
| 01 | Exploratory Data Analysis | Missing values, descriptive statistics, visualisation, correlation | [Program](ex-01/ex-01.py) · [README](ex-01/README.md) | [Notebook](ex-01/ex-01.ipynb) |
| 02 | Simple Linear Regression | Regression line, slope, intercept, MSE, R² | [Program](ex-02/ex-02.py) · [README](ex-02/README.md) | [Notebook](ex-02/ex-02.ipynb) |
| 03 | Multiple Linear Regression | Multiple predictors, encoding, regression metrics | [Program](ex-03/ex-03.py) · [README](ex-03/README.md) | [Notebook](ex-03/ex-03.ipynb) |
| 04 | Polynomial Regression | Polynomial features, degree-2 curve, regression metrics | [Program](ex-04/ex-04.py) · [README](ex-04/README.md) | [Notebook](ex-04/ex-04.ipynb) |
| 05 | Ridge Regression | L2 regularisation, polynomial features, overfitting | [Program](ex-05/ex-05.py) · [README](ex-05/README.md) | [Notebook](ex-05/ex-05.ipynb) |
| 06 | Lasso Regression | L1 regularisation, feature shrinkage, overfitting | [Program](ex-06/ex-06.py) · [README](ex-06/README.md) | [Notebook](ex-06/ex-06.ipynb) |
| 07 | Logistic Regression | Binary classification, confusion matrix, ROC-AUC | [Program](ex-07/ex-07.py) · [README](ex-07/README.md) | [Notebook](ex-07/ex-07.ipynb) |
| 08 | K-Nearest Neighbors | Distance-based classification, choosing K | [Program](ex-08/ex-08.py) · [README](ex-08/README.md) | [Notebook](ex-08/ex-08.ipynb) |
| 09 | Decision Tree | Tree classifier, classification metrics, visualisation | [Program](ex-09/ex-09.py) · [README](ex-09/README.md) | [Notebook](ex-09/ex-09.ipynb) |
| 10 | Random Forest | Ensemble classification, ROC-AUC | [Program](ex-10/ex-10.py) · [README](ex-10/README.md) | [Notebook](ex-10/ex-10.ipynb) |
| 11 | Support Vector Machine | Linear, polynomial, RBF and sigmoid kernels | [Program](ex-11/ex-11.py) · [README](ex-11/README.md) | [Notebook](ex-11/ex-11.ipynb) |
| 12 | Hyperparameter Tuning | GridSearchCV, cross-validation, SVC | [Program](ex-12/ex-12.py) · [README](ex-12/README.md) | [Notebook](ex-12/ex-12.ipynb) |
| 13 | K-Means Clustering | Inertia, Elbow Method, cluster labels | [Program](ex-13/ex-13.py) · [README](ex-13/README.md) | [Notebook](ex-13/ex-13.ipynb) |
| 14 | Hierarchical Clustering | Ward linkage, agglomerative clustering, dendrogram | [Program](ex-14/ex-14.py) · [README](ex-14/README.md) | [Notebook](ex-14/ex-14.ipynb) |
| 15 | DBSCAN Clustering | Density-based clusters, noise points, PCA visualisation | [Program](ex-15/ex-15.py) · [README](ex-15/README.md) | [Notebook](ex-15/ex-15.ipynb) |
| 16 | Principal Component Analysis | Dimensionality reduction, principal components, explained variance | [Program](ex-16/ex-16.py) · [README](ex-16/README.md) | [Notebook](ex-16/ex-16.ipynb) |

## Learning Outcomes

Through these practical exercises, the lab record covers:
- Exploring and summarising datasets, identifying missing values and visualising relationships.
- Building linear, polynomial and regularised regression models.
- Training and evaluating classification models using appropriate metrics.
- Comparing kernels and tuning model hyperparameters with cross-validation.
- Exploring unsupervised learning through K-Means, hierarchical clustering and DBSCAN.
- Reducing dimensionality with PCA and interpreting explained variance.

## Technology Stack

- **Language:** Python
- **Data handling:** pandas, NumPy
- **Visualisation:** Matplotlib, seaborn
- **Machine learning:** scikit-learn
- **Hierarchical clustering visualisation:** SciPy where used
- **Interactive format:** Jupyter Notebook

Package requirements can vary by exercise. See the exercise README and [dataset guide](datasets/README.md) before running a program.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Joerakesh/machine_learning_lab.git
cd machine_learning_lab
```

### 2. Create a virtual environment

Linux / macOS:
```bash
python -m venv .venv
source .venv/bin/activate
```

Windows PowerShell:
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 3. Install libraries

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Add datasets

Place each dataset at the relative path expected by its program. Current expected names include `Dataset/titanic.csv`, `Dataset/Salary.csv`, `Dataset/Housing.csv`, `Dataset/fish.csv`, and `heart_disease_dataset.csv`. Verify the exact path in the relevant exercise README. Dataset files may not be included because they can have separate licensing or distribution terms. See [datasets/README.md](datasets/README.md).

### 5. Run a Python program or notebook

For a standalone program:
```bash
cd ex-01
python ex-01.py
```

To run a notebook, start Jupyter from the repository root:
```bash
jupyter notebook
```
Then open the notebook for the relevant exercise. Run cells from top to bottom. Saved outputs will appear in the notebook after execution; GitHub can display saved notebook outputs once the executed notebook is committed.

## Results & Academic Notes

Each exercise README includes its aim, algorithm/workflow, dataset path, links to the Python program and notebook, and the result summary transcribed from the supplied practical record. Metrics and summaries are record-reported, not independently revalidated in this repository update. Perfect or unusually high classification scores should be reviewed for data leakage, duplicate records, and evaluation design before being interpreted as evidence of generalisation.

## Repository Features

- **Exercise notebooks:** interactive code and rendered outputs after execution.
- **Experiment READMEs:** consistent academic documentation.
- **Dataset guide:** expected file names and data-source reminders.
- **Dependencies:** [requirements.txt](requirements.txt) lists the shared lab libraries.
- **Output figures:** [assets/outputs/README.md](assets/outputs/README.md) explains where to keep generated charts.
- **GitHub Actions:** lightweight Python syntax checks.
- **Issue templates:** structured bug reports and documentation questions.
- **Citation metadata:** [CITATION.cff](CITATION.cff).
- **License:** [LICENSE](LICENSE); review whether these terms fit the rights and intended reuse of all materials.

## Maintainer

**Joe Rakesh A** · [GitHub profile](https://github.com/Joerakesh)

Department of Data Science · Loyola College, Chennai.

---

<div align="center">

*Machine Learning Laboratory · I M.Sc. Data Science · 2026–2027*

</div>
