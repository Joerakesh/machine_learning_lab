# Dataset Guide

This folder documents datasets used by the Machine Learning Laboratory programs.

## Dataset register

| Dataset filename / expected path | Used by | How to obtain it | Redistribution status |
|---|---|---|---|
| `Dataset/titanic.csv` | Exercise 01 — EDA | Add the exact source URL or download instructions after verification | Verify before committing |
| `Dataset/Salary.csv` | Check the relevant exercise README | Add the exact source URL or download instructions after verification | Verify before committing |
| `Dataset/Housing.csv` | Check the relevant exercise README | Add the exact source URL or download instructions after verification | Verify before committing |
| `Dataset/fish.csv` | Check the relevant exercise README | Add the exact source URL or download instructions after verification | Verify before committing |
| `heart_disease_dataset.csv` | Exercise 09 — Decision Tree | Add the exact source URL or download instructions after verification | Verify before committing |

This list is based on dataset paths mentioned in the current root documentation and exercise material. Confirm every dataset-to-exercise mapping and source before treating this as a complete register.

## Dataset handling guidelines

- Prefer linking to the original dataset source when redistribution is not permitted.
- Do not commit confidential, licensed, or unnecessarily large data files.
- Document the expected file name, relative path, target column, and any required download steps.
- Keep real-world data separate from generated outputs and notebooks.
- For every experiment, record the dataset version or source URL so results can be reproduced.

## Local folder example

For a script expecting `Dataset/titanic.csv`, place that file at the path the script expects relative to its execution context. Check each exercise's README before moving or renaming data.
