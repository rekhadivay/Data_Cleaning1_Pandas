# Data Cleaning Steps
## Load Data:
Read the dataset from an Excel file into a Pandas DataFrame.

## Remove Duplicates:
Eliminate duplicate rows to ensure unique records in the dataset.

## Remove Unnecessary Column:
Drop a column that is not useful for the analysis.

## Clean "Last_Name" Column:
Strip extraneous characters from the "Last_Name" entries.

## Clean "Phone_Number" Column:
Standardize phone numbers by removing non-numeric characters and formatting them as xxx-xxx-xxxx.

## Split "Address" Column:
Divide the "Address" column into separate columns for street address, state, and zip code.

## Clean "Do_Not_Contact" Column:
Standardize values in the "Do_Not_Contact" column, replacing 'Yes' with 'Y' and 'No' with 'N'.

## Remove Rows Based on Conditions:
Remove rows where "Do_Not_Contact" is 'Y' or the "Phone_Number" is empty.

## Reset Index:
Reset the DataFrame index for a clean representation of the cleaned dataset.