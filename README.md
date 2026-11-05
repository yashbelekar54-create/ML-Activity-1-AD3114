# CIE 2 – Machine Learning Activities 1 and 2

This folder contains two independently organized practical activities prepared according to the supplied Zeal College of Engineering and Research CIE 2 Machine Learning instructions (2026–27).

## Folder structure

```text
CIE2_ML_Activities/
├── README.md
├── Activity_1_Dataset_Preparation/
│   ├── README.md
│   ├── Activity_1_Dataset_Preparation.ipynb
│   ├── data/
│   │   └── student_learning_habits_raw.csv
│   └── outputs/
│       ├── student_learning_habits_prepared.csv
│       ├── missing_values_before_cleaning.csv
│       └── *.png
└── Activity_2_House_Price_Prediction/
    ├── README.md
    ├── Activity_2_House_Price_Prediction.ipynb
    ├── data/
    │   └── residential_property_prices_raw.csv
    └── outputs/
        ├── regression_metrics.csv
        ├── test_actual_vs_predicted.csv
        ├── new_example_prediction.csv
        ├── linear_regression_house_price_pipeline.joblib
        └── *.png
```

## Important dataset provenance disclosure

The two CSV datasets included here are **synthetic educational datasets generated locally**, not real student or property records and not downloaded from an external open-data repository. They are intentionally designed to demonstrate missing-value handling, duplicates, categorical inconsistencies, exploratory analysis and regression. Fixed random seeds make the datasets reproducible.

The supplied CIE instructions prefer a reliable open-source or academic dataset. If the faculty interprets that requirement strictly, replace the included synthetic CSV with a properly cited public dataset and rerun the corresponding notebook. Do not describe these generated records as real-world or public-source data.

**All notebook code reads the CSV files from the local `data/` folders.** It does not load data from GitHub URLs, APIs or remote dataset loaders.

## How to run

1. Extract the ZIP file.
2. Open the relevant activity folder in Jupyter Notebook, JupyterLab or Google Colab.
3. Open the `.ipynb` file.
4. Ensure the `data/` folder remains beside the notebook.
5. Run all cells from top to bottom.
6. The notebooks have been executed and saved with visible outputs. Re-running them regenerates the output files and charts.

Python packages used: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `joblib`, and Jupyter.

Install if needed:

```bash
pip install pandas numpy matplotlib scikit-learn joblib jupyter
```

## GitHub publication

The CIE instructions require a **separate public GitHub repository for each activity**, with a clear repository name that identifies the activity and roll number. Each activity folder includes its own README template. Before publication, replace `[YOUR_ROLL_NUMBER]` in the suggested repository name with your actual roll number, review the notebooks and outputs, and upload the relevant activity folder contents to its own public repository.

The faculty acknowledgement requested in the CIE instructions is included in each activity README. The faculty profile is linked as requested: https://github.com/Princy2129.

## Academic integrity and verification

The notebooks show actual results generated from the included CSVs. Review the data provenance note, execute the notebooks yourself, understand the decisions, and ensure the final submission reflects your own work and your faculty's requirements. No repository has been published on your behalf.
