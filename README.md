# Personal Expense Tracker

A beginner-friendly Python project for recording, analyzing, and storing personal expenses.

## Features

- Add expenses by date
- Add expenses by category
- Calculate daily expenses
- Calculate total expenses
- Calculate category-wise spending
- Find the highest individual expense
- Find the highest spending day
- Convert expense data into a Pandas DataFrame
- Save expense data to CSV
- Read expense data from CSV

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- CSV
- `datetime`

## Project Structure

```text
Personal-Expense-Tracker/
├── Personal_Expense_Tracker.ipynb
├── expenses.csv
├── README.md
└── .gitignore
```

## Example Data

| Date | Grocery | Books | Others |
|---|---:|---:|---:|
| 2026-10-05 | ₹100 | ₹2000 | ₹10 |
| 2026-10-04 | ₹120 | ₹1200 | ₹50 |

## Example Results

- **Total expense:** ₹3480
- **Highest individual expense:** Books — ₹2000
- **Highest spending day:** 05/10/2026 — ₹2110

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/prakash-thunder/Personal-Expense-Tracker.git
```

2. Enter the project directory:

```bash
cd Personal-Expense-Tracker
```

3. Open the notebook with Jupyter:

```bash
jupyter notebook
```

4. Open `Personal_Expense_Tracker.ipynb` and run the cells.

## Learning Objectives

This project practices:

- Variables and data types
- Dictionaries and lists
- Loops
- Conditional statements
- Functions
- Date handling
- File handling
- Pandas DataFrames
- CSV files
