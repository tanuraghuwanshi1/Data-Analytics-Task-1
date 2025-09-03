# Stress Level Dataset — Task 1 (Data Cleaning)

## Objective
Clean and preprocess the raw dataset by checking nulls, removing duplicates, standardizing text,
fixing data types, and renaming columns. Output a clean CSV ready for analysis or modeling.

## Files
- `StressLevelDataset.csv` — raw dataset
- `StressLevelDataset_Cleaned.csv` — cleaned dataset (generated)
- `data_cleaning.ipynb` — notebook with all steps

## Summary of Results
- Initial → Final Shape: preserved (no rows removed, unless duplicates existed)
- Missing values: none in the provided file; generic handling code included
- Duplicates: none found
- Text standardized to lowercase & stripped
- Types coerced where possible (numeric/datetime)
- Columns renamed to snake_case

## How to Run Locally
1. Install **Anaconda** (recommended) or **Python 3.10+**.
2. Open **Jupyter Notebook** or **JupyterLab**.
3. Put the three files above in the same folder.
4. Open `data_cleaning.ipynb` and run all cells.
5. The cleaned file will be saved as `StressLevelDataset_Cleaned.csv`.

## Notes
- Adjust missing value strategy as needed for your use case.
- Keep this repository focused on Task 1 only, as per Skillytixs instructions.