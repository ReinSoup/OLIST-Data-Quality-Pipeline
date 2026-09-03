# Olist Data Quality Pipeline

An end-to-end data cleaning and validation project using the Olist e-commerce dataset.

The project demonstrates how raw, inconsistent datasets can be inspected, cleaned, validated, and transformed into analysis-ready data and a structured SQLite database using Python and pandas.

## Project Goals

The goal of this project is to build a reproducible data-cleaning workflow rather than simply produce a cleaned dataset.

The workflow covers:

- Raw data inspection
- Data quality assessment
- Missing-value analysis
- Duplicate detection
- Data type correction
- Text normalization
- Date standardization
- Validation of cleaned data
- Exporting cleaned datasets
- Loading cleaned data into SQLite

## Project Structure

```text
olist-data-quality-pipeline/
│
├── data/
│   ├── raw/
│   │   └── Original Olist datasets
│   │
│   ├── cleaned/
│   │   └── Cleaned and validated datasets
│   │
│   └── database/
│       └── SQLite database
│
├── notebooks/
│   ├── Data inspection
│   ├── Data cleaning
│   └── Data validation
│
├── src/
│   └── Reusable Python cleaning code
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Workflow

```text
Raw Olist Data
      ↓
Data Inspection
      ↓
Identify Quality Issues
      ↓
Data Cleaning
      ↓
Validation
      ↓
Cleaned Data
      ↓
SQLite Database
```

## Tools Used

- Python
- pandas
- NumPy
- Jupyter Notebook
- SQLite
- SQLAlchemy
- Matplotlib
- Seaborn

## Data

The project uses the Olist Brazilian e-commerce dataset.

The original raw datasets are included in `data/raw/` so that the complete transformation from raw data to cleaned data can be examined.

The raw files are kept unchanged.

## Project Status

🚧 In progress

The project is being developed progressively, with each stage of the data-cleaning workflow documented and validated.

## Author

ABDUL RAB (Ryan)

