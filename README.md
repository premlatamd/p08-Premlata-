# Breast Cancer Classification

## Dataset
This project uses the Breast Cancer Wisconsin Diagnostic dataset (`wdbc.data`). It contains 569 samples, an ID column, a diagnosis label, and 30 numeric diagnostic features. The diagnosis labels are B (Benign) and M (Malignant).

## Dataset Source and Licence
Source: UCI Machine Learning Repository — Breast Cancer Wisconsin (Diagnostic) dataset.

Dataset page: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

Please check the dataset page for the applicable licence and usage conditions.

## How to Obtain the Dataset
Download the dataset files from the source above. Place `wdbc.data` in the project directory before running the notebooks. The data file has no header row, so load it using the column names defined in the notebook.

## Random Seeds
The train-test split uses `random_state=42` and stratification by diagnosis. Cross-validation and randomized hyperparameter search also use a fixed random seed of 42 where specified in the code.

## Project Files
- `scratch.ipynb`: Scratch implementations and agreement tests (R3).
- `comparison.ipynb`: Data audit, model comparison, tuning, repeated cross-validation, final evaluation, and model trade-offs (R1, R2, R4, R5, R6, R7).
- `decision.md`: R5 limitations and final model decision (R8).

## How to Run
1. Install Python and the required packages: `pandas`, `numpy`, `scikit-learn`, and `matplotlib`.
2. Download `wdbc.data` and place it in the project directory.
3. Open `scratch.ipynb` and run the cells from top to bottom.
4. Open `comparison.ipynb` and run the cells from top to bottom.
5. Review `decision.md` for the model-selection decision and limitations.