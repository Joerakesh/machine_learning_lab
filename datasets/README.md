# Dataset Guide

This guide lists dataset paths referenced by the Machine Learning Lab practical record and current exercise programs. The dataset files themselves are not bundled here. Confirm the exact path in the corresponding Python program before running it.

## Dataset register

| Dataset | Exercises | Purpose |
|---|---|---|
| `Dataset/titanic.csv` | 01 — Exploratory Data Analysis | Passenger attributes and survival |
| `Dataset/Salary.csv` | 02 — Simple Linear Regression | Salary prediction from years of experience |
| `Dataset/Housing.csv` | 03, 05, 06 — Multiple Linear, Ridge and Lasso Regression | House-price prediction and regularisation |
| `Dataset/fish.csv` | 04 — Polynomial Regression | Fish weight prediction from measurements |
| `heart_disease_dataset.csv` | 07–16 — Classification, model tuning, clustering and PCA | Heart disease classification and unsupervised learning |

The table is based on the supplied Machine Learning Lab practical record. If a program uses a slightly different relative path or filename, follow the literal path in that program.

## Dataset sourcing

- Obtain datasets from their original or otherwise authorised source.
- Add the source URL, access date/version and relevant attribution to the exercise README when known.
- Do not commit data files if the dataset licence or privacy terms do not permit redistribution.
- Do not upload sensitive or personally identifiable data.
- Keep the filename and relative path consistent with the program unless you intentionally configure a different local path.

## Running scripts and notebooks

For relative paths such as `Dataset/titanic.csv`, open a terminal in the corresponding exercise directory before running the script. Notebooks are also located inside each exercise directory, so run them from that folder and confirm the dataset is at the expected relative path.

## Reproducibility checklist

For each experiment, record:
- Dataset source and version
- Python and relevant package versions
- Preprocessing and train/test split settings
- Random seed where applicable
- Actual metrics and plots produced by your run

Do not treat the result summaries in the exercise READMEs as fresh runs: they are transcribed from the practical record supplied for this repository.
