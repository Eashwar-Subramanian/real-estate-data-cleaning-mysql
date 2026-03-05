# Real Estate Data Cleaning (MySQL)

End-to-end data cleaning workflow on the Nashville housing dataset using MySQL (standardization, parsing, normalization, and de-duplication).

## What’s in this repo
- `Nashville Housing Data for Data Cleaning.csv` — original dataset
- `Nashville Housing Data for Data Cleaning_SQL.sql` — full MySQL cleaning script

## Cleaning operations included (as implemented in the SQL script)
- Standardize sale date formats into a consistent date field
- Populate missing property addresses using existing records
- Split property address into structured components
- Split owner address into address / city / state
- Normalize categorical fields (e.g., Y/N → Yes/No)
- Identify and remove duplicates
- Drop unused columns after restructuring

## How to run
1) Import the CSV into MySQL as a table
2) Run `Nashville Housing Data for Data Cleaning_SQL.sql` top-to-bottom

## Feedback I want
Open a GitHub Issue titled: **Review: real-estate-data-cleaning-mysql** and tell me:
1) If the script is easy to follow without extra context  
2) Whether comments + step ordering are clear  
3) What you’d change to make this feel more “production-style”
