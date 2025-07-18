# DSA-project-Palmoria-group-HR-analysis
This repository contains a data analysis project focused on cleaning, transforming, and enriching HR employee data for Palmoria Group.

## Files Included

- `Palmoria_Enriched_Employee_Data.xlsx`: Final cleaned dataset with calculated bonuses and total compensation.
- `Palmoria_HR_Bonus_Analysis_Report.docx`: Step-by-step documentation outlining all processing and logic applied.
- `Palmoria Group emp-data.csv`: Original employee dataset.
- `Palmoria Group Bonus Rules.xlsx`: Departmental bonus rule matrix used for calculations.

## Summary of Analysis

- Cleaned missing values for gender and removed invalid salary or department entries.
- Normalized performance ratings for consistency.
- Transformed the bonus matrix (with departments as rows and ratings as columns) into a long format usable for merging.
- Merged the employee data with bonus rules based on `Department` and `Rating`.
- Computed `Bonus Amount` as `Salary × Bonus %` and calculated `Total Compensation`.

## Tools Used
- Python (pandas, openpyxl)
- Excel for verification

## How to Use
1. Clone this repo or download the files.
2. Open the Excel file to explore the final results.
3. Refer to the Word report for full documentation of each step.

## Author
- Jaob Omoghonrinme Elizabeth| Capstone Project | DSA Program
