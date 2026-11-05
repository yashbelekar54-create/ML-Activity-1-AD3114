# Activity 1 – Dataset Preparation Activity

**Unit I – Foundations & Data Preparation | 5 Marks | Online**

## Objective
Inspect a tabular dataset, identify data-quality issues, perform basic EDA, handle missing values, check duplicates and consistency, encode categorical features, scale suitable numerical features, and save a separate prepared CSV. No prediction model is built.

## Dataset and provenance
- File: `data/student_learning_habits_raw.csv`
- Dataset: Student Learning Habits and Academic Performance
- Raw shape: 522 rows × 9 columns
- Prepared shape: 520 rows × 14 columns
- Provenance: locally generated synthetic educational data using a fixed random seed. It contains no real student records and must not be represented as a public or real-world dataset.
- It includes missing values, two duplicate rows, inconsistent category formatting and one deliberately invalid study-hours value for the cleaning demonstration.

**CIE source requirement note:** The instructions prefer a reliable open-source or academic dataset. This generated dataset is transparently disclosed. If an externally sourced dataset is mandatory, substitute one with a verifiable citation and rerun the notebook.

## Files
- `Activity_1_Dataset_Preparation.ipynb` – detailed, executed notebook covering all ten activity steps.
- `data/student_learning_habits_raw.csv` – untouched original CSV.
- `outputs/student_learning_habits_prepared.csv` – cleaned, one-hot encoded and standardized CSV.
- `outputs/missing_values_before_cleaning.csv` – missing-value count and percentage report.
- `outputs/01_exam_score_histogram.png` – examination-score distribution.
- `outputs/02_study_method_bar_chart.png` – categorical frequency visualization.
- `outputs/03_study_hours_vs_score.png` – relationship visualization.

## Preparation decisions
- Numerical missing values: median imputation.
- Categorical missing values: mode imputation.
- Invalid study hours (>16 hours/day): marked missing, then imputed.
- Exact duplicate rows: removed after inspection.
- Nominal categories: one-hot encoded.
- Numerical input features: standardized.
- `student_id`: retained as an identifier, not scaled or encoded.
- `final_exam_score`: retained as a possible target, not scaled.

## Run locally
Open the notebook from this folder and run all cells. It reads the included local CSV using a relative path; no GitHub URL or API is used.

## Suggested public repository name
`ML-CIE2-Activity1-Dataset-Preparation-[YOUR_ROLL_NUMBER]`

## Faculty profile and acknowledgement
Faculty profile: https://github.com/Princy2129

Include this acknowledgement in the public repository README:

> This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: https://github.com/Princy2129

Each student must create and maintain their own public repository. Do not request access to or attempt to modify the faculty's GitHub account.
