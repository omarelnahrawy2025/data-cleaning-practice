# data-cleaning-practice
Python data cleaning and preprocessing practice using Pandas and NumPy as part of my research internship at the Lithuanian Energy Institute.
## Practical Data Cleaning – Household Electricity Consumption

## Household Electricity Consumption — Data Cleaning and Analysis

### Completed Work

- Missing value detection and treatment.
- Short-gap linear interpolation.
- Duplicate detection.
- Data type and timestamp correction.
- Inconsistent data investigation.
- Outlier detection using the IQR method.
- Hourly, daily and monthly electricity consumption analysis.
- Data visualisation.

### Key Results

| Parameter | Result |
|---|---:|
| Original observations | 2,075,259 |
| Cleaned observations | 2,049,352 |
| Interpolated observations | 72 |
| Removed observations | 25,907 |
| Remaining missing values | 0 |
| Duplicate records | 0 |
| Flagged outliers | 94,919 |
| Average active power | 1.092 kW |
| Minimum active power | 0.076 kW |
| Maximum active power | 11.122 kW |
| Peak demand hour | 20:00 |
| Lowest demand hour | 04:00 |

### Visualisations

- Average hourly electricity consumption.
- Daily electricity consumption over time.
- Average daily electricity consumption by month.
- Distribution of household active power.

### Tools and Libraries

Python, Pandas, NumPy, Matplotlib and Jupyter Notebook.

### Dataset Source

https://www.kaggle.com/raghvendrat/uci-household-energy-demand-consumption-dataset
