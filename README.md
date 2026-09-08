# India CPI Inflation Analysis — Excel

> End-to-end analysis of India's Consumer Price Index (CPI) using Excel to investigate inflation trends, category contribution, food inflation, COVID-19 effects, and the relationship between crude oil prices and CPI categories.

---

## Overview

This project is an end-to-end Excel data analytics case study based on India's Consumer Price Index (CPI) data covering **January 2013 to May 2023**.

The objective was to transform a structured CPI dataset into meaningful analytical insights by cleaning and validating the data, creating broader analytical categories, calculating derived inflation metrics, evaluating relationships between variables, and presenting the findings through an executive dashboard.

The project investigates five key analytical questions:

- How much does each broader CPI category represent within the analytical CPI basket?
- How has year-over-year CPI inflation changed from 2017 to 2023?
- How has food inflation changed over the 12 months ending May 2023?
- How did inflation behavior change around the March 2020 COVID-19 onset?
- How are imported crude-oil price movements associated with CPI-category inflation?

---

## Problem Statement

Inflation is influenced by multiple categories of goods and services, and its behavior can vary significantly across time and sectors.

The objective of this analysis was to use historical CPI data to identify:

1. The relative contribution of broader CPI categories within the project's analytical basket.
2. Major changes in year-over-year inflation.
3. Trends and fluctuations in food inflation.
4. Changes in inflation behavior around the COVID-19 period.
5. The relationship between imported crude-oil price changes and CPI-category inflation.

The analysis was designed to move beyond simple visualization by using formula-driven calculations and statistical techniques to investigate the underlying patterns in the data.

---

## Dataset

**Source:** Government of India, Ministry of Statistics and Programme Implementation (MoSPI)

**Coverage:** January 2013 – May 2023

**Sectors:**
- Rural
- Urban
- Rural + Urban (Combined)

The workbook contains the original source layer as well as a cleaned, analysis-ready dataset.

A dedicated **Data Dictionary** documents the fields, validation checks, cleaning/standardization steps, assumptions, and derived metrics used throughout the analysis.

### Data Structure

The main CPI dataset contains monthly observations across multiple CPI categories and the three sector classifications.

The project also retains the original data separately from the cleaned dataset to maintain traceability between the source and analytical layers.

---

## Tools & Technologies

### Microsoft Excel

The project was developed entirely in Microsoft Excel using:

- Excel Tables
- Structured References
- Formula-driven calculations
- Data validation
- Conditional formatting
- Charts and visualizations
- Dashboard design

### Excel Functions Used

- `INDEX`
- `MATCH`
- `SUMIFS`
- `AVERAGE`
- `IF`
- `MAX`
- `MIN`
- `ROWS`
- `COLUMNS`
- `COUNTA`
- `UNIQUE`
- `DATEDIF`
- `CORREL`

---

## Methods & Analytical Approach

### 1. Data Cleaning & Validation

The raw CPI data was structured into an analysis-ready table while preserving the original source data.

Validation included:

- Checking the date range
- Checking the number of sectors
- Verifying expected versus actual row counts
- Standardizing the analytical structure
- Documenting assumptions and data limitations

The workbook contains **375 data rows across 31 columns**, covering 125 monthly observations across the three sector classifications.

---

### 2. Broader Category Contribution

For the latest month, individual CPI sub-categories were grouped into broader analytical buckets such as:

- Food
- Apparel
- Health
- Fuel & Light
- Education
- Transport & Communication
- Housing
- Household Goods & Services
- Recreation & Amusement
- Personal Care & Effects
- Miscellaneous
- Pan, Tobacco & Intoxicants
