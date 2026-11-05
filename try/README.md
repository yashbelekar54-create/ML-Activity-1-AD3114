# Machine Learning CIE 2 – Activities 1 and 2

This package contains two Google Colab/Jupyter notebooks prepared according to the CIE 2 activity instructions.

## Activity 1 – Dataset Preparation
- Dataset: scikit-learn Diabetes dataset (442 rows; public dataset).
- A derived `bmi_category` field demonstrates categorical processing.
- A few missing values are deliberately introduced in the working copy to demonstrate imputation; they are not original source missing values.
- Includes inspection, summary statistics, missing-value handling, duplicate checks, EDA visualizations, one-hot encoding, standardization and CSV export.
- `prepared_dataset.csv` is the prepared output.
- `diabetes_eda_source_with_demo_missing.csv` is the working input with demonstration missing values.

Dataset documentation: https://scikit-learn.org/stable/datasets/toy_dataset.html#diabetes-dataset

## Activity 2 – Simple House Price Prediction
- Dataset: California Housing dataset from scikit-learn.
- Feature: `MedInc` (median income).
- Target: `MedHouseVal` (median house value; units of $100,000).
- Model: single-feature Linear Regression.
- Includes 80:20 split, coefficient/intercept, test predictions, MAE, MSE, RMSE, R², actual-versus-predicted plot and one new prediction.
- The dataset is downloaded when the notebook is run in an internet-enabled environment such as Google Colab.

Dataset documentation: https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset

## How to run
1. Open each `.ipynb` file in Google Colab.
2. Select **Runtime → Run all**.
3. For Activity 1, download the generated `prepared_dataset.csv` from the Colab file panel (the included CSV is also provided).
4. For Activity 2, ensure the notebook runtime has internet access so scikit-learn can fetch the dataset.
5. Review the actual outputs, and add your name, roll number, division and any faculty-required details before submission.

## GitHub publication
Create a separate **public** GitHub repository for each activity. Use a repository name that includes the activity and your roll number. Upload the relevant notebook, dataset/output files and README. Follow the faculty profile and acknowledgement instructions in each notebook.

Faculty profile: https://github.com/Princy2129

Acknowledgement to include:
> This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: https://github.com/Princy2129

**Important:** Run Activity 2 before submitting so the notebook contains real execution outputs and metric values. Do not report results that have not been obtained.
