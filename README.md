# Real Estate Data Cleaning (MySQL)

Data cleaning workflow for the Nashville housing dataset using MySQL statements (standardization, parsing, and de-duplication).

---

## What this repo contains
- Original CSV dataset
- A single SQL script implementing the cleaning steps end-to-end

---

## Cleaning operations included
- Standardize sale dates into a consistent format
- Populate missing property address values using existing records
- Split property address into structured components
- Split owner address into address/city/state
- Normalize categorical fields (e.g., Y/N to Yes/No)
- Identify and remove duplicates
- Drop unused columns after restructuring

---

## Files
- `Nashville Housing Data for Data Cleaning.csv`
- `Nashville Housing Data for Data Cleaning_SQL.sql`

---

## Review request
Open an Issue titled: **Review: real-estate-data-cleaning-mysql**  
Feedback wanted: SQL structure, comments, and clarity for someone scanning quickly.
