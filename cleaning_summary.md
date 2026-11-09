# Data Cleaning Summary - Mall Customers Dataset

## Changes Performed:
1. **Column Normalization:** Converted all column headers to lowercase and replaced spaces with underscores (e.g., `Annual Income (k$)` $\rightarrow$ `annual_income_k$`) for easier querying.
2. **Missing Values Check:** Inspected dataset for null values and applied median imputation for numerical features and placeholder filling for categorical features.
3. **Duplicate Removal:** Checked for and dropped duplicate rows to maintain data integrity. 
4. **Text Standardization:** Cleaned up the `gender` column values to ensure consistent casing (`Male`, `Female`).
5. **Data Type Validation:** Ensured numerical columns (`age`, `annual_income_k$`, `spending_score_1-100`) possess correct integer/float data types. 
