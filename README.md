Importing Data:
Load the dataset (e.g., CSV, Excel) using pandas or any preferred tool.
Handling Missing Values:
Identify missing values using .isnull().sum().
Fill missing values using techniques like mean/median imputation (for numeric fields), or mode/imputation (for categorical fields).
Drop irrelevant columns/rows if too many values are missing.

Data Type Conversion:
Convert columns like "Date of Sale" to datetime format.
Ensure numerical columns like "Sales", "Revenue", "Price" are in float/int format.
Convert string/object columns to categorical where applicable.

Duplicate Removal:
Check and remove duplicates using .duplicated() and .drop_duplicates().

Outlier Detection:
Use boxplots, Z-score, or IQR methods to detect outliers in numeric fields like "Sales", "Revenue".
Treat or remove outliers depending on context.

Standardizing & Normalizing:
Clean inconsistent entries in categorical fields (e.g., "Pop", "pop", "POP" → "Pop").
Normalize numerical fields if needed for modeling.

Date & Time Processing:
Extract useful features like Year, Month, Day, Weekday from date fields.
Ensure time-based trends or seasonality can be analyzed.

Removing Irrelevant Columns:
Drop columns that don’t contribute to analysis (e.g., unnecessary IDs, notes).

Encoding Categorical Data:
Convert categorical variables into numerical format using Label Encoding or One-Hot Encoding for model readiness.

Data Validation:
Cross-check cleaned data for consistency and correctness.
Ensure business rules are met (e.g., no negative sales values).
