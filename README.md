# Five Vital Signs Healthcare Data Analysis with Python

## Overview

This project explores a healthcare dataset containing repeated measurements of five vital signs across 102 subjects:

* Heart Rate
* Systolic Blood Pressure
* Diastolic Blood Pressure
* Oxygen Saturation
* Temperature

The project demonstrates how Python can be used to organize, analyze, visualize, and interpret healthcare data.

## Objective

The main objective was to investigate the distribution and variability of the five vital signs and explore whether meaningful linear relationships existed between them.

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Jupyter / Google Colab
* Descriptive Statistics
* Correlation Analysis
* Data Visualization

## Analysis Performed

### 1. Data Inspection

* Loaded and inspected the dataset
* Examined the dataset structure and variables
* Checked for missing values

### 2. Data Transformation

The dataset contained multiple readings for each vital sign. I calculated the average reading for each subject to create a simplified subject-level dataset.

### 3. Descriptive Statistics

| Vital Sign        |        Mean | Median | Standard Deviation |
| ----------------- | ----------: | -----: | -----------------: |
| Heart Rate        |   82.14 bpm |  81.39 |              10.77 |
| Systolic BP       | 105.72 mmHg | 106.61 |               8.76 |
| Diastolic BP      |  69.94 mmHg |  70.72 |               6.21 |
| Oxygen Saturation |      97.45% |  97.67 |               1.17 |
| Temperature       |     36.10°C |  36.20 |               0.59 |

## Key Findings

* Heart rate showed the greatest variability among the five measurements.
* Temperature showed the smallest variability.
* Mean and median values were relatively close across the variables.
* No missing values were identified in the dataset.
* The correlation between average heart rate and average systolic blood pressure was approximately **0.023**, indicating an almost negligible linear relationship in this dataset.
* Other pairs of vital signs also showed generally weak linear correlations.

## Healthcare Relevance

This project demonstrates a basic healthcare-data workflow that can be applied to clinical datasets.

In a hospital environment, similar analysis could be used to examine patient vital-sign records, monitor trends, investigate unusual measurements, and generate data-driven insights.

This project focuses on **data analysis rather than clinical diagnosis or medical decision-making**.

## Conclusion

The project provided practical experience working with healthcare data using Python. It covered data inspection, transformation, descriptive statistics, visualization, and correlation analysis.

The main takeaway was that healthcare datasets can contain multiple measurements that need to be transformed into useful summaries before meaningful analysis can be performed.

## Dataset

The dataset used for this project is **Five Vital Signs of Normal People**.

Source: Zenodo

## Author

**Richard Fajorin**

Biomedical Engineering | Data Analysis | Python | Power BI | SQL
