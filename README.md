# datathon2023
This is the repo for MD+ datathon 2023 project

Steps to reproduce the result.


## Step 0 Loading data

The MIMIC-IV hosp module need to be downloaded into a database, e.g., duckdb in our case, with schemas as the MIMIC-IV suggested.

## Step 1 Cohort building

step1_cohort_building.ipynb can be runned sequentially from loading data from the database to build the cohort, at last, the cohort data was outputted as csv named "main_df.csv"

## Step 2 Analysis step

After setting libraries and directory, step2_Analysis.qmd can be sequentially to load csv data and generate tables, figures listed in the report.
