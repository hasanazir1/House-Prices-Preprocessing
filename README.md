# House Prices Data Preprocessing

This project applies data preprocessing steps on the House Prices - Advanced Regression Techniques dataset.

## Assignment Goal

The goal is to prepare a clean and processed training set that is ready for regression modeling.

## Dataset

The dataset contains information about residential homes in Ames, Iowa.

Files used:

- `train.csv`
- `test.csv`

The files should be placed inside a folder named `data`.

## Project Steps

1. Data Retrieval
2. Dataset Inspection
3. Memory Management
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Engineering
7. Reusable Preprocessing Function
8. Saving Processed Data

## Main Work Done

- Loaded training and testing datasets.
- Checked dataset shape, columns, and data types.
- Handled missing values using suitable strategies.
- Removed clear outliers based on `GrLivArea` and `SalePrice`.
- Applied log transformation to `SalePrice`.
- Created EDA visualizations.
- Created a new feature called `TotalSF`.
- Applied ordinal encoding and one-hot encoding.
- Created final processed datasets ready for regression modeling.

## How to Run

1. Download `train.csv` and `test.csv` from Kaggle.
2. Create a folder named `data`.
3. Put both files inside the `data` folder.
4. Open `House_Prices_Preprocessing.ipynb`.
5. Run all cells from top to bottom.

## Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt

## Output

The processed files are saved inside the `processed_data` folder:

- `X_train_processed.csv`
- `X_test_processed.csv`
- `y_train_log.csv`

## Author

Machine Learning Assignment 1
