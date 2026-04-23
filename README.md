## **Public Revenue Execution Analysis in Brazil (2013–2021)**


## Overview
This project analyzes how effectively Brazilian public institutions executed projected public revenue between **2013 and 2021**. Each year, government agencies https://github.com/marta-ba/brazil-public-revenue-execution-analysis/blob/main/README.mdestimate how much revenue they expect to collect, but actual collection often differs due to factors such as tax evasion, economic fluctuations, administrative inefficiencies, and structural issues.

The project combines multiple datasets, normalizes them, and analyzes them jointly to identify **patterns, recurring underperformance, and inefficiencies in revenue execution** across agencies and administrative units.

---

## Project Objective
Identify patterns and problematic areas where actual revenue collection consistently fell below forecasted revenue over a **7-year period (2013–2021)**.

---

## Specific Objectives

- **Measure deviations between forecasted and collected revenue**  
  Determine which economic categories or revenue types show the largest gaps.

- **Analyze the evolution of revenue collection over time**  
  Examine how forecasts and actual collections changed year by year, and detect temporal patterns such as months with larger discrepancies.

- **Evaluate performance by agency and management unit**  
  Identify which government bodies and administrative units were more efficient in meeting revenue targets, and which consistently underperformed.

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
An exploratory analysis was conducted on each dataset individually to:

- Understand variable structure and data quality
- Identify relevant dimensions for comparison
- Detect outliers and inconsistencies
- Explore patterns in revenue forecasts and execution

### 2. Data Normalization and Integration
After cleaning and standardizing the datasets, they were merged into a unified analytical dataset to evaluate the system as a whole.

### 3. Comparative and Temporal Analysis
The final dataset was used to:

- Compare forecasted vs. actual revenue
- Measure absolute and relative deviations
- Analyze performance across years, agencies, and management units
- Detect consistency and volatility in revenue execution

---

## Main Findings

### Agencies with the lowest execution rates
The analysis identified public institutions with the lowest average budget execution rates. Among the most critical cases were:

- **Hospital Cristo Redentor S.A.**
- **Brazilian Space Agency**

Both showed an **average execution rate below 6%**.

This reveals critical areas where planning and budget execution require substantial improvement.

### Agencies with the highest inconsistency
The institutions with the greatest variability in execution over time included:

- **Ministry of the Environment (linked units)**
- **Federal Data Processing Service**

This suggests unstable financial planning and difficulty allocating resources efficiently over time.

### Evolution of key variables over time
When evaluating **Forecast**, **Actual Revenue**, **Absolute Difference**, and **Deviation Percentage**, the analysis found that:

- **Forecast** and **Actual Revenue** remained relatively stable over time, suggesting consistency in total budget planning but no significant improvement in results.
- **Deviation Percentage** followed a fairly uniform trend, which may indicate a lack of meaningful adjustments in forecasting or execution methodology.

---

## Key Insights

- Some public institutions consistently fail to meet projected revenue targets.
- Low execution rates and high volatility suggest structural inefficiencies in planning and resource management.
- Stable forecasts over time, without performance improvement, may indicate limited institutional learning from previous years.
- Certain agencies should be prioritized for targeted intervention and monitoring.

---

## Conclusions

### Inefficient budget planning in key institutions
Agencies with both **low execution rates** and **high inconsistency** demonstrate weaknesses in budget management, whether due to poor planning, inadequate execution, or structural limitations.

### Limited improvement over time
The relative stability in forecasted and actual revenue suggests that there have been **no major corrective efforts** to improve execution performance across the years.

### Opportunity for institutional improvement
A more dynamic forecasting and evaluation process could improve public revenue execution and resource allocation efficiency.

---

## Recommendations

- Prioritize agencies with low execution rates for operational review.
- Investigate root causes behind underperformance, including planning issues, resource allocation problems, or policy execution barriers.
- Implement stronger monitoring systems for agencies with high volatility.
- Improve forecasting methodologies using more adaptive evaluation mechanisms.
- Strengthen institutional capacity through better processes, training, and technology.

---

## Tech Stack

**Language:** Python 3.8

**Main Libraries:**

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## Project Structure

```bash
.
├── data/                # Raw and processed data
├── Proyecto_EDA_Brasil/ # Jupyter notebooks with the analysis
├── src/                 # Data processing and modeling scripts
├── results/             # Charts and output files
└── README.md            # Project documentation
