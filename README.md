# Website Exploration & Data Mining in Crime Analysis (Project 1)

**Course:** DATA MINING (CSE 632) – Fall 2025  
**University:** University of Louisville, Computer Science & Engineering  
**Student:** Rupa Ghosh  
**Submission Date:** September 18, 2025   

---

## Overview
This project explores crime incident data from Los Angeles (2020–Present) using data mining and exploratory analysis techniques. The goal is to preprocess real-world data, engineer meaningful features, and test hypothesis-driven patterns related to crime type, seasonality, time of occurrence, victim age, and residential location.

The project emphasizes **clean data handling**, **reproducibility**, and **clear visual interpretation** rather than predictive modeling.

---

## Dataset
- **Source:** data.gov  
- **Dataset name:** *Crime Data from 2020 to Present*  
- **Format:** CSV  

The raw dataset is **not included** in this repository due to file size constraints.


Additional instructions are available in `data/README.md`.

---

## Preprocessing & Feature Engineering
The following preprocessing steps were applied:

- Feature selection based on hypothesis relevance
- Standardization of column names
- Missing value handling
- Date and time formatting
- Feature creation:
- Year, month, weekday
- Daypart (morning, afternoon, evening, night)
- Age groups
- Crime classification into:
- Violent
- White-collar
- Other
- Residential location categorization:
- Single-family
- Multi-family

Processed datasets are saved in the `output/` directory.

---

## Hypotheses Tested
1. **Seasonality:**  
White-collar crimes decrease during summer months, while violent crimes increase.

2. **Time & Age Concentration:**  
Violent crimes are more concentrated during evening/night hours, particularly among young adults (ages 18–29), and this pattern increases over time.

3. **Residential Location:**  
Single-family residences experience a higher share of violent crimes compared to multi-family residences.

---

## Visual Analysis
The project uses multiple visualization techniques, including:

- Bar charts
- Line plots
- Donut charts
- Heatmaps

Key figures are saved in the `figures/` directory.  
Selected highlights are shown below.

### Feature Selection Summary
![Feature Selection](figures/feature_selection_kept_vs_dropped.png)

### Seasonal Crime Trends
![Seasonal Trends](figures/summer_vs_nonsummer_trends.png)

### Residential Crime Distribution
![Residential Heatmap](figures/home_type_heatmap.png)

Additional figures are available in the `figures/` folder.


---

## How to Run
1. Clone this repository
2. Download the dataset and place it in `data/`
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

