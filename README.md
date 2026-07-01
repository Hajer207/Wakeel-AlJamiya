# Wakeel Al-Jamiya – Data Pipeline

## Overview

This repository contains the complete data engineering workflow for the Wakeel Al-Jamiya project.

The goal is to transform raw financial data into a synthetic Jamiya dataset that can be consumed by AI agents for risk assessment, member prioritization, and turn management.

---

## Project Structure

```
Wakeel-AlJamiya-Data/
│
├── data/
│   ├── 01_Raw_Credit_Dataset.csv
│   ├── 02_Cleaned_Dataset.csv
│   ├── 03_Synthetic_Jamiya_Dataset.csv
│   └── 04_Data_Dictionary.xlsx
│
├── scripts/
│   ├── preprocess.py
│   ├── check_data.py
│   └── feature_engineering.py
│
├── dashboard/
│   └── Dashboard.xlsx
│
├── docs/
│   ├── Data_Cleaning_Report.md
│   ├── Feature_Engineering.md
│   └── References.md
│
├── requirements.txt
└── README.md
```

---

## Data Pipeline

Raw Dataset

↓

Data Cleaning

↓

Feature Engineering

↓

Synthetic Jamiya Dataset

↓

Risk Agent

↓

Turn Agent

---

## Technologies

- Python
- Pandas
- NumPy
- OpenPyXL
- Matplotlib

---

## Features

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Feature Engineering
- Trust Score Generation
- Risk Classification
- Synthetic Dataset Creation

---

## Dataset

The project uses a public credit risk dataset as the initial source.

The data is cleaned and transformed into a synthetic Jamiya dataset suitable for AI Agent workflows.

---

## Authors

Wakeel Al-Jamiya Team