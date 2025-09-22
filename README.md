# ELEVATE_LABS_DATA-ANALYST_INTERN_TASK-1
# Task 1 - Data Cleaning and Preprocessing

## Dataset
- **Name:** Customer Personality Analysis (marketing_campaign.csv)
- **Rows:** 2240 (raw)
- **Columns:** 29

## Cleaning Steps
1. Filled missing `Income` with median.
2. Removed duplicates.
3. Standardized `Education` and `Marital_Status`.
4. Converted `Dt_Customer` to datetime (dd-mm-yyyy).
5. Renamed columns to snake_case.
6. Ensured correct data types.
7. Treated outliers:
   - Removed invalid `year_birth` (<1900 or >2025).
   - Removed extreme incomes (>200,000).

## Deliverables
- `raw_data/marketing_campaign.csv`
- `cleaned_data/cleaned_marketing_campaign.csv`
- `cleaning_steps_excel.md`

## Tools Used
- Excel (manual cleaning)


---
📌 **This cleaned dataset is ready for analysis or modeling.**
