# Real-world Data Cleaning & SQL Analytics Project

## Overview
This project demonstrates a complete, end-to-end workflow for handling a real-world dataset:
from raw data exploration and cleaning using Python, to structured analysis using SQL.

The focus of this project is **data quality**, **reproducibility**, and **clear engineering workflow**,
rather than model building or visualization.

---

## Dataset

- Dataset name: FIFA 21 Raw Data
- File: `fifa21 raw data v2.csv`
- Source: Kaggle (public dataset)
- Domain: Sports / Player attributes

> ⚠️ The raw CSV file is **not included** in this repository.
> Please download the dataset manually and place it under:
>
> ```text
> data/raw/
> ```

---

## Project Structure

```text
public-data-cleaning-sql/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── data/
│   ├── raw/        # original raw dataset (unchanged)
│   └── cleaned/    # cleaned / processed data
│
├── scripts/
│   ├── 01_explore.py   # data exploration & quality assessment
│   ├── 02_clean.py     # data cleaning & transformation
│   └── 03_load_sql.py  # load cleaned data into SQL database
│
├── sql/
│   ├── schema.sql      # table definitions
│   └── queries.sql     # analytical queries
│
├── outputs/
│   ├── figures/        # optional plots
│   └── reports/        # analysis summaries
