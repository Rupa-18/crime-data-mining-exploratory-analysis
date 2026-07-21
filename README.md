# Crime Data Mining and Exploratory Analysis

## Overview

This project analyzes over one million crime records from the **Los Angeles Crime Data (2020–Present)** dataset using data mining and exploratory analysis techniques. The objective is to clean and preprocess real-world data, engineer meaningful features, and investigate crime patterns related to seasonality, victim demographics, time of occurrence, and residential locations.

The project emphasizes reproducible data analysis, statistical reasoning, and effective visualization rather than predictive modeling.

---

## Dataset

**Source:** Data.gov

**Dataset:** Crime Data from 2020 to Present

**Format:** CSV

The raw dataset is not included in this repository due to its large file size.

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Hypothesis Testing
- Statistical Analysis
- Data Visualization
- Pattern Discovery

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Preparation

The dataset was prepared using the following preprocessing pipeline:

- Feature selection based on analysis objectives
- Standardization of column names
- Missing value handling
- Date and time formatting
- Temporal feature engineering
  - Year
  - Month
  - Weekday
  - Daypart (Morning, Afternoon, Evening, Night)
- Demographic feature engineering
  - Age groups
- Crime categorization
  - Violent Crimes
  - White-Collar Crimes
  - Other Crimes
- Residential location categorization
  - Single-Family
  - Multi-Family

---

## Research Questions

This project investigates three hypothesis-driven questions:

### 1. Seasonality

Do white-collar crimes decrease during summer months while violent crimes increase?

### 2. Time and Victim Age

Are violent crimes more concentrated during evening and night hours, particularly among young adults (18–29), and has this pattern changed over time?

### 3. Residential Location

Do single-family residences experience a higher proportion of violent crimes than multi-family residences?

---

## Key Visualizations

### Age Group Distribution

<p align="center">
<img src="figures/age_group_distribution.png" width="700">
</p>

---

### Crime Distribution by Time of Day

<p align="center">
<img src="figures/daypart_distribution.png" width="700">
</p>

---

### Summer Crime Trends

<p align="center">
<img src="figures/summer_monthly_crimes_by_year.png" width="700">
</p>

---

### Violent Crimes at Residential Locations

<p align="center">
<img src="figures/violent_crimes_residence_heatmap.png" width="700">
</p>

---

## Key Findings

- Cleaned and analyzed a real-world dataset containing over one million crime records.
- Engineered temporal and demographic features to support meaningful exploratory analysis.
- Investigated seasonal, temporal, and residential crime patterns through hypothesis-driven analysis.
- Produced multiple visualizations to communicate crime trends and support analytical conclusions.

---


## How to Run

Clone the repository

```bash
git clone https://github.com/Rupa-18/crime-data-mining-exploratory-analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Download the **Los Angeles Crime Data (2020–Present)** dataset from Data.gov and place it inside the `data/` directory before running the notebooks or scripts.

---

