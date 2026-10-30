# Kodbud Data Science Internship — Four Beginner Projects

I selected four of the eight options because they are small, cover different beginner skills, and can be completed with local Python scripts:

1. **Task 2 — Titanic survival prediction:** prepare passenger data and train Logistic Regression.
2. **Task 5 — Salary prediction:** fit Linear Regression and calculate Mean Squared Error.
3. **Task 6 — Correlation heatmap:** visualize correlations in student scores.
4. **Task 8 — Data cleaning:** handle missing data, convert dates and treat an outlier.

## Setup

Install Python 3, then in a terminal run:

```bash
python -m pip install -r requirements.txt
```

Run each script from this folder, for example:

```bash
python task5_salary/salary_prediction.py
```

Scripts create their output files beside themselves in an `outputs` subfolder. The salary, scores and cleaning examples are small **demonstration datasets created by the scripts**, not real-world data. Mention that in any presentation.

## Task 2 data

Download `train.csv` from the Kaggle Titanic competition data page and put it in `task2_titanic/train.csv`. The script uses only the training data and a held-out test split; it does not submit predictions to Kaggle. It prints accuracy and a classification report and saves a confusion matrix. Dataset source: [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic/data).

## Submission checklist from the task sheet

- Make a short video explaining what you built and post it on LinkedIn, tagging Kodbud.
- GitHub upload is optional but recommended.
- Submit your completed task link(s) through the Task Submission Form in your email.

Do not publish personal offer-letter details in project posts.
