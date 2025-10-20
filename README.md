Data Cleaning Summary:

Loaded the customer dataset using Pandas.

Checked for missing values and handled them.

Converted the income column to numeric, replacing non-numeric values with NaN, then filled missing values with the median.

Removed duplicate rows to ensure data quality.

Standardized column names to UPPERCASE_WITH_UNDERSCORES.

Converted columns to appropriate data types:

YEAR_BIRTH → integer

INCOME → float

Converted DT_CUSTOMER to datetime format with dayfirst=True, then formatted as d/m/YYYY for consistency:

Saved the cleaned dataset as cleaned_marketing_campaign.csv for further analysis.
