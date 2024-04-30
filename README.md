# Stats_for_ds
Statistics project for Data Science -01
# Heart Failure Prediction Project

## Overview
This project aims to analyze heart failure clinical records dataset to predict the likelihood of heart failure and explore factors associated with patient outcomes. The dataset contains various clinical and demographic variables for heart failure patients, including age, sex, anaemia, high blood pressure, diabetes, smoking status, serum creatinine levels, ejection fraction, etc.

## Dataset
The dataset used in this project is the Heart Failure Clinical Records Dataset, which can be found in the file `heart_failure_clinical_records.csv`. It contains the following columns:

- `age`: Age of the patient (years)
- `anaemia`: Whether the patient has anaemia (0 = No, 1 = Yes)
- `creatinine_phosphokinase`: Level of creatinine phosphokinase in the blood (mcg/L)
- `diabetes`: Whether the patient has diabetes (0 = No, 1 = Yes)
- `ejection_fraction`: Percentage of blood leaving the heart at each contraction (%)
- `high_blood_pressure`: Whether the patient has high blood pressure (0 = No, 1 = Yes)
- `platelets`: Platelets in the blood (kiloplatelets/mL)
- `serum_creatinine`: Level of serum creatinine in the blood (mg/dL)
- `serum_sodium`: Level of serum sodium in the blood (mEq/L)
- `sex`: Gender of the patient (0 = Female, 1 = Male)
- `smoking`: Whether the patient smokes (0 = No, 1 = Yes)
- `time`: Follow-up period (days)
- `DEATH_EVENT`: Whether the patient died during the follow-up period (0 = No, 1 = Yes)

## Analysis
### Exploratory Data Analysis (EDA)
- Explored the distribution of variables using histograms, box plots, and scatter plots.
- Investigated relationships between variables to identify potential predictors of heart failure and patient outcomes.

### Data Preprocessing
- Checked for missing values and handled them appropriately (e.g., imputation).
- Detected and handled outliers using the IQR method.
- Standardized or normalized numerical variables as required.

### Statistical Analysis
- Performed t-tests to compare means between patients who survived and those who didn't for numerical variables.
- Conducted chi-square tests to analyze the association between categorical variables and patient outcomes.

### Results
- Summarized the results of statistical tests and provided conclusions based on significance levels.
- Identified factors significantly associated with heart failure and patient mortality.

## Conclusion
Based on the analysis conducted, age, ejection fraction, serum creatinine, serum sodium, and follow-up period (time) were found to be significantly associated with patient outcomes. Anaemia, high blood pressure, diabetes, sex, and smoking status did not show significant associations with patient mortality in this dataset.

## References
- Dataset Source: [Heart Failure Clinical Records Dataset](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data)
