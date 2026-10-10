# Machine Learning Laboratory — M.Sc. Data Science

A structured collection of 16 Machine Learning Laboratory exercises for postgraduate Data Science learning. This repository preserves the original Python programs and provides a place for experiment notes, reproducible results, and Jupyter notebooks.

> **Scope:** Exploratory Data Analysis, Regression, Classification, Clustering, Hyperparameter Tuning, and Dimensionality Reduction.

## Repository at a glance

| Item | Details |
|---|---|
| Level | Postgraduate — M.Sc. Data Science |
| Exercises | 16 |
| Language | Python |
| Core libraries | pandas, NumPy, Matplotlib, seaborn, scikit-learn |
| Additional libraries | SciPy where required |
| Formats | Standalone Python scripts, experiment documentation, and Jupyter notebooks as they are added |

## Experiment index

| No. | Experiment | Area | Python script | Notebook |
|---:|---|---|---|---|
| 01 | Exploratory Data Analysis | Data analysis | [ex-01.py](ex-01/ex-01.py) | Planned: `ex-01.ipynb` |
| 02 | Simple Linear Regression | Regression | [ex-02.py](ex-02/ex-02.py) | Planned: `ex-02.ipynb` |
| 03 | Multiple Linear Regression | Regression | [ex-03.py](ex-03/ex-03.py) | Planned: `ex-03.ipynb` |
| 04 | Polynomial Regression | Regression | [ex-04.py](ex-04/ex-04.py) | Planned: `ex-04.ipynb` |
| 05 | Ridge Regression | Regularization | [ex-05.py](ex-05/ex-05.py) | Planned: `ex-05.ipynb` |
| 06 | Lasso Regression | Regularization | [ex-06.py](ex-06/ex-06.py) | Planned: `ex-06.ipynb` |
| 07 | Logistic Regression | Classification | [ex-07.py](ex-07/ex-07.py) | Planned: `ex-07.ipynb` |
| 08 | K-Nearest Neighbors (KNN) | Classification | [ex-08.py](ex-08/ex-08.py) | Planned: `ex-08.ipynb` |
| 09 | Decision Tree | Classification | [ex-09.py](ex-09/ex-09.py) | Planned: `ex-09.ipynb` |
| 10 | Random Forest | Ensemble learning | [ex-10.py](ex-10/ex-10.py) | Planned: `ex-10.ipynb` |
| 11 | Support Vector Machine (SVM) | Classification | [ex-11.py](ex-11/ex-11.py) | Planned: `ex-11.ipynb` |
| 12 | Hyperparameter Tuning | Model selection | [ex-12.py](ex-12/ex-12.py) | Planned: `ex-12.ipynb` |
| 13 | K-Means Clustering | Clustering | [ex-13.py](ex-13/ex-13.py) | Planned: `ex-13.ipynb` |
| 14 | Hierarchical Clustering | Clustering | [ex-14.py](ex-14/ex-14.py) | Planned: `ex-14.ipynb` |
| 15 | DBSCAN Clustering | Clustering | [ex-15.py](ex-15/ex-15.py) | Planned: `ex-15.ipynb` |
| 16 | Principal Component Analysis (PCA) | Dimensionality reduction | [ex-16.py](ex-16/ex-16.py) | Planned: `ex-16.ipynb` |

Each exercise folder contains its Python program and an exercise README with code and recorded output. Notebook links will be added after notebooks have been created and verified.

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/Joerakesh/machine_learning_lab.git
cd machine_learning_lab
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

Linux / macOS:

```bash
source .venv/bin/activate
```

Windows PowerShell:

```powershell
.venv\\Scripts\\Activate.ps1
```

### 3. Install dependencies

Install the libraries required by the individual experiment. A root-level `requirements.txt` can be used once the dependency list has been verified against the scripts.

### 4. Run an experiment

Run a script from its own exercise folder so relative dataset paths work as expected:

```bash
cd ex-01
python ex-01.py
```

Some programs expect datasets at paths such as `Dataset/titanic.csv`, `Dataset/Salary.csv`, `Dataset/Housing.csv`, `Dataset/fish.csv`, or `heart_disease_dataset.csv`. Check the corresponding exercise README for the expected filename and location before running. Dataset files are not assumed to be included in this repository.

## What each experiment documents

For a consistent postgraduate lab record, each exercise page should provide:

1. **Objective** — What the experiment investigates.
2. **Dataset** — Source, observations, features, target (if applicable), and data dictionary.
3. **Methodology** — Preprocessing, algorithm, important parameters, and train/test strategy where applicable.
4. **Implementation** — Link to the original Python program and the notebook when available.
5. **Results** — Actual console output, tables, and generated plots.
6. **Evaluation** — Suitable metrics such as MAE/RMSE/R² for regression, precision/recall/F1/confusion matrix for classification, or appropriate cluster analysis for clustering.
7. **Interpretation and limitations** — What the results indicate, assumptions, limitations, and a concise conclusion.

Report only results produced by running the program with the documented dataset and environment. Do not infer or invent scores or outputs.

## Results and visualizations

GitHub can render committed Jupyter notebooks with saved outputs, including many tables and static plots. For important figures, store a lightweight PNG in an exercise-specific folder under `assets/outputs/` and embed it in the relevant README, for example:

```markdown
![Decision tree confusion matrix](../assets/outputs/ex-09/confusion-matrix.png)
```

Ensure screenshots and plots correspond to the current code and dataset. Avoid committing large datasets or generated files that can be recreated unless there is a clear reason.

## Data and reproducibility

- Use only datasets you are allowed to redistribute; otherwise document the source and download instructions.
- Record relevant package versions when reproducibility matters.
- Fix random seeds where the experiment already uses them.
- Explain train/test splitting and the evaluation metric used.
- Treat unusually perfect model scores as a prompt to investigate data leakage, target construction, duplicate records, and evaluation design—not as proof of a perfect real-world model.
- Keep original practical code unchanged when adding documentation or notebooks; clearly disclose any separate exploratory analysis.

## Suggested development workflow

- Keep one clearly named branch for each meaningful change.
- Use GitHub Issues to track missing outputs, documentation tasks, and reproducibility problems.
- Use pull requests to review significant changes, even when working independently.
- Use GitHub Actions for lightweight syntax/import checks where they can run safely without private datasets.
- Add a release or tag when you want to mark a stable version of the lab record.

## Academic use

This repository is a learning and reference portfolio. Verify the official course syllabus, experiment titles, datasets, and submission requirements with your department. Cite original dataset sources and any external references you use.

## Maintainer

Maintained by [Joe Rakesh](https://github.com/Joerakesh).

---

If you find an issue in a program, dataset path, or explanation, open a GitHub Issue with the exercise number and the steps needed to reproduce it.
