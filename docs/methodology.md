# Project Methodology

## Overview

This project follows the Cross-Industry Standard Process for Data Mining (CRISP-DM), a widely adopted methodology for planning and executing data analytics projects.

The methodology provides a structured framework that guides the project from understanding the business problem to delivering meaningful insights.

---

# CRISP-DM Process

Business Understanding
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Exploratory Data Analysis
        ↓
Visualization
        ↓
Insights & Recommendations

---

## 1. Business Understanding

### Objective

Analyze monthly student performance data from the KSHRD Basic Course to identify learning trends, evaluate academic performance, and generate actionable insights.

### Business Questions

- How has student performance changed over time?
- Which class performs the best?
- Does attendance influence academic performance?
- Which students improve the most?
- How do Class Leaders compare with other students?

---

## 2. Data Understanding

The dataset consists of four monthly worksheets:

- March 2026
- April 2026
- May 2026
- June 2026

Each worksheet contains student-level academic performance records.

During this phase, the dataset is inspected to understand:

- Dataset structure
- Data types
- Missing values
- Duplicate records
- Data consistency
- Assessment structure

No modifications are made to the original dataset during this phase.

Notebook:
- `00_understanding_data.ipynb`

---

## 3. Data Preparation

The monthly reports are standardized and merged into a single master dataset.

Tasks include:

- Standardizing column names
- Adding a Month column
- Handling missing values
- Resolving inconsistent data
- Merging worksheets
- Exporting the cleaned dataset

Output:

- `student_performance_cleaned.csv`
- `student_performance_cleaned.xlsx`

Notebook:
- `01_data_preparation.ipynb`

---

## 4. Exploratory Data Analysis (EDA)

The cleaned dataset is analyzed to answer the project's business questions.

Analyses include:

- Overall student performance
- Monthly performance trends
- Student progress
- Subject analysis
- Attendance analysis
- Scholarship analysis
- Class performance
- Student status analysis

Notebook:
- `02_exploratory_data_analysis.ipynb`

---

## 5. Data Visualization

Visualizations are created to communicate the analysis effectively.

Examples include:

- Line charts
- Bar charts
- Pie charts
- Scatter plots
- Histograms
- Correlation heatmaps

Notebook:
- `03_visualization.ipynb`

---

## 6. Insights & Recommendations

The final stage summarizes the analytical findings and provides recommendations based on the observed trends.

Examples include:

- Academic performance trends
- Student improvement
- Attendance recommendations
- Class performance comparisons
- Future monitoring suggestions

---

# Repository Workflow

Raw Data
      ↓
Understanding
      ↓
Preparation
      ↓
EDA
      ↓
Visualization
      ↓
Insights