# datathon2023
This is the repo for MD+ datathon 2023 project

Steps to reproduce the result.


## Loading data

The MIMIC-IV need to loaded into a database named MIMIC_IV.duckdb, e.g., duckdb in our case, with schemas as the MIMIC-IV suggested.

## Cohort building

step1_cohort_building.ipynb can be runned sequentially to build the cohort, at last, the cohort data was outputted as csv named "main_df.csv"

## Analysis step

After setting libraries and directory, step2_Analysis.qmd can be sequentially to load csv data and generate tables, figures listed in the report.
