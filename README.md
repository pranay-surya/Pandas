# Pandas Tutorial — From Basics to Data Manipulation

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.x-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)

---

## Overview

This repository is a structured, topic-wise Pandas workbook built for learners who want to develop strong data manipulation skills through practical Jupyter Notebooks. Each notebook isolates a specific concept and demonstrates it through real usage patterns encountered in data analysis and machine learning workflows.

The content progresses from foundational data structures to advanced reshaping operations, making it suitable both for beginners getting started with Pandas and for practitioners looking to consolidate their understanding before applying it in analytics or ML pipelines.

---

## Repository Structure

```
Pandas/
|-- 01. Pandas - Series.ipynb
|-- 02. Pandas - DataFrame.ipynb
|-- 03. Pandas - read_csv_basic.ipynb
|-- 04. Pandas - read_csv_parameter.ipynb
|-- 05. Pandas - NAN value drop.ipynb
|-- 06. Pandas - fill NAN values.ipynb
|-- 07. Pandas - replace.ipynb
|-- 08. Pandas - interpolate.ipynb
|-- 09. Pandas - loc & iloc.ipynb
|-- 10. Pandas - group by.ipynb
|-- 11. Pandas - concat & join.ipynb
|-- 12. Pandas - Pivot table.ipynb
|-- 13. Pandas - melt function.ipynb
|-- 14. Pandas - merge.ipynb
|-- README.md
```

---

## Notebook Contents

### Pandas Basics

Covers the two primary data structures in Pandas — Series and DataFrame — which form the foundation of all further operations.

| No. | Notebook | Key Concepts |
|---|---|---|
| 01 | Pandas Series | Creation, indexing, slicing, element-wise operations |
| 02 | Pandas DataFrame | Construction, column access, structure inspection, basic analysis |

---

### Data Importing

Focuses on reading external data into Pandas, with emphasis on the flexibility of `read_csv()` and its parameters.

| No. | Notebook | Key Concepts |
|---|---|---|
| 03 | read_csv — Basic | Loading CSV files, default behavior, DataFrame preview |
| 04 | read_csv — Parameters | `nrows`, `usecols`, `skiprows`, `index_col`, `header`, `dtype` |

---

### Handling Missing Values

Demonstrates the four primary strategies for dealing with missing or null data (`NaN`) in real-world datasets.

| No. | Notebook | Key Concepts |
|---|---|---|
| 05 | dropna | Removing rows/columns with missing values, threshold control |
| 06 | fillna | Forward fill, backward fill, constant fill, column-wise strategies |
| 07 | replace | Substituting specific values or patterns across a DataFrame |
| 08 | interpolate | Linear and index-based interpolation for sequential and time-series data |

---

### Data Selection

Covers label-based and position-based indexing, which are essential for extracting subsets of data cleanly and efficiently.

| No. | Notebook | Key Concepts |
|---|---|---|
| 09 | loc and iloc | Row/column selection by label (`loc`) and integer position (`iloc`), conditional filtering |

---

### Data Aggregation

Introduces grouping and aggregation — core operations for summarizing datasets by category.

| No. | Notebook | Key Concepts |
|---|---|---|
| 10 | groupby | Split-apply-combine pattern, aggregation functions (`sum`, `mean`, `count`, `agg`) |

---

### Data Combination and Reshaping

Covers the methods used to combine multiple DataFrames and restructure data between wide and long formats.

| No. | Notebook | Key Concepts |
|---|---|---|
| 11 | concat and join | Vertical/horizontal concatenation, index-based joining |
| 12 | Pivot Table | Multi-level summarization, `aggfunc`, margins |
| 13 | melt | Wide-to-long transformation, `id_vars`, `value_vars` |
| 14 | merge | SQL-style joins — inner, left, right, outer — on keys and indexes |

---

## Prerequisites

| Requirement | Version |
|---|---|
| Python | 3.8 or above |
| Pandas | 1.5 or above |
| NumPy | 1.21 or above |
| Jupyter Notebook | Any recent version |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/pranay-surya/Pandas.git
cd Pandas

# Install dependencies
pip install pandas numpy jupyter

# Launch Jupyter Notebook
jupyter notebook
```

---
