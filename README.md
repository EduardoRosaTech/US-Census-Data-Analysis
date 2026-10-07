# Demographic & Economic Data Analysis

**Python • Exploratory analysis • Data visualization • Simulated educational data**

A Python case study comparing income and exploring relationships between income, poverty, and education across five state-level records.

## Problem

How can a demographic and economic dataset be summarized and visualized to support clear analytical questions? This project demonstrates an EDA workflow, with careful limits on interpreting a very small sample.

## Data

[us_census.csv](us_census.csv) contains fields for `State`, `Income`, `Population`, `Poverty`, and `Bachelor_or_Higher`. The notebook's recorded output contains **five rows**.

**The original README explicitly labels the data as simulated for educational purposes. It is not presented here as an authenticated U.S. Census extract.** For an analysis using official statistics, obtain and document an appropriate source from [data.census.gov](https://data.census.gov).

## Methodology

1. Load the CSV and strip whitespace from column names.
2. Inspect data types and descriptive statistics with `info()` and `describe()`.
3. Sort the records by income and create a bar chart.
4. Calculate Pearson correlations for income, poverty, and bachelor's-degree attainment and display a heatmap.

## Technologies

**Python, Pandas, Matplotlib, Seaborn, Jupyter / Google Colab.**

## Analysis and results

The recorded summary reports income values from **59,606 to 75,277**, with a mean of **66,459.4**, in the five-row example. The bar chart compares income across records; the heatmap summarizes associations among the three selected variables.

These values describe the educational dataset only. Five simulated observations cannot support population-level conclusions, causal claims, or policy recommendations. No interactive dashboard is included in the repository.

## Explore and reproduce

Open [US_Census_Data_Analysis.ipynb](US_Census_Data_Analysis.ipynb). In Google Colab, upload `us_census.csv` to `/content/`, matching the notebook's current input path, then run the analysis cells. The actual repository stores the notebook, CSV, and `requirements.txt` at the root.

## Possible extensions

Use a documented official dataset, expand coverage, and add a Power BI dashboard. These are proposed extensions, not implemented features.
