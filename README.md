# Indian Defence Budget Analytics 🇮🇳📊

## Project Overview

This project analyzes India's defence budget using year-wise **Budget Estimate (BE) - Projected** and **BE - Allocated** values.

The analysis covers **2014-15 to 2021-22** and focuses on budget growth, allocation rate, and the gap between projected and allocated amounts.

## Objectives

- Compare projected and allocated defence budgets across years
- Measure the allocation rate
- Calculate the projected-vs-allocated gap
- Analyze year-over-year growth in allocated budget
- Identify important trends and findings through visualizations

## Dataset

**File:** `RS_Session_253_AU1455.A.csv`

The dataset contains the year-wise budget figures used in the notebook.

> Note: The dataset is kept as a separate CSV file so the project remains easy to reproduce and maintain.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Analysis

The notebook calculates:

1. **Allocation Gap** = Projected Budget − Allocated Budget
2. **Allocation Rate (%)** = Allocated Budget / Projected Budget × 100
3. **YoY Growth (%)** in allocated budget

## Key Findings

Based on the supplied notebook/data analysis:

- **Projected budget growth:** 58.23%
- **Allocated budget growth:** 54.30%
- **Average allocation rate:** 76.62%
- **Average projected-vs-allocated gap:** ₹82,918.18 crore
- **Highest allocated budget:** 2021-22 — ₹3,24,657.56 crore
- **Largest gap:** 2021-22 — ₹1,24,850.89 crore

These findings are descriptive results from the supplied dataset and should not be interpreted as causal conclusions.

## Visualizations

The notebook includes visual analysis for:

- Projected vs Allocated Defence Budget
- Allocation Rate by Year
- Year-over-Year Growth in Allocated Budget

## Project Structure

```text
Indian_Defence_Budget_Analytics/
│
├── Indian_Defence_Budget_Analytics.ipynb
├── RS_Session_253_AU1455.A.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd Indian_Defence_Budget_Analytics
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook Indian_Defence_Budget_Analytics.ipynb
```

Run all cells from top to bottom.

## Skills Demonstrated

- Data cleaning
- Exploratory Data Analysis (EDA)
- Data transformation
- Percentage and growth calculations
- Data visualization
- Insight generation
- Python/Pandas/NumPy
- Matplotlib
- Jupyter Notebook
- GitHub project organization

## Future Improvements

- Add more recent financial years
- Add category-wise defence expenditure analysis
- Build an interactive Power BI/Tableau dashboard
- Add filters for different budget components
- Compare defence budget trends with GDP or other macroeconomic indicators

## Author

**Vanshika Chaudhary**

A beginner-friendly data analytics project focused on extracting meaningful insights from public budget data.
