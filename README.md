# Missing Value Analysis

A beginner-friendly Python project to identify and analyze missing values in a dataset using Pandas and NumPy.

## Objective

To identify missing values, calculate column-wise missing-value counts and percentages, and determine which columns require data cleaning.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Concepts Used

- `pd.DataFrame()` – creates a DataFrame
- `isnull()` – identifies missing values
- `sum()` – counts missing values
- `shape` – checks dataset dimensions
- Missing-value percentage calculation
- Boolean conditions – identify columns requiring treatment

## Dataset

The project uses a sample student dataset with six records and four columns:

- Name
- Age
- Marks
- Department

Missing values are intentionally included to demonstrate missing-value analysis.

## Results

| Column | Missing Count | Missing Percentage |
|---|---:|---:|
| Name | 0 | 0.00% |
| Age | 2 | 33.33% |
| Marks | 2 | 33.33% |
| Department | 1 | 16.67% |

Total missing values: 5.

Columns requiring treatment: Age, Marks, and Department.

## Explanation

The dataset was examined using Pandas to identify missing values in each column.

The total number and percentage of missing values were calculated. A summary table was created to make the results easier to understand.

The analysis identified three columns that may require missing-value treatment before machine learning.

## How to Run

1. Open `Missing_Value_Analysis.ipynb` in VS Code or Jupyter Notebook.
2. Install the required libraries if necessary using `pip install pandas numpy`.
3. Select the Python kernel.
4. Run all cells from top to bottom.
5. Review the missing-value summary and report.

## Learning Outcome

- Learned to identify missing values using Pandas.
- Practiced calculating missing-value counts and percentages.
- Created a column-wise missing-value summary.
- Identified columns requiring data cleaning.
- Understood why missing-value analysis is important before machine learning.

## Project Structure

```text
Missing-Value-Analysis/
│
├── Missing_Value_Analysis.ipynb
└── README.md
```