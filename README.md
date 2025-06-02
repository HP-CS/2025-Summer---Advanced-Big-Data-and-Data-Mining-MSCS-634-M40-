# 2025-Summer---Advanced-Big-Data-and-Data-Mining-MSCS-634-M40-

# MSCS 634 - Lab 1: Data Visualization, Data Preprocessing, and Statistical Analysis

## Purpose
This lab demonstrates data visualization, data preprocessing, and statistical analysis using Python in Jupyter Notebook.

## Dataset
The dataset used in this lab is `Economy_of_US.csv`, which includes GDP, inflation, and unemployment data from 1980 to 2027.

## Key Insights
- **Visualization**: Inflation trends were visualized using scatter and line plots.
- **Preprocessing**: Missing values were handled using mean imputation and forward fill.
- **Outliers**: Detected and removed using the IQR method.
- **Scaling**: GDP values were normalized using Min-Max Scaling.
- **Statistical Summary**: Central tendency and dispersion metrics were calculated.

## Challenges & Decisions
- Forward fill was chosen for missing time series values to preserve continuity.
- IQR was more effective than Z-score due to skewed distribution.

## 📁 Files Included
- `Lab1_Final.ipynb`: The complete notebook with all steps.
- `Economy_of_US.csv`: Dataset used.
- `screenshots/`: Folder containing required screenshots for submission.
