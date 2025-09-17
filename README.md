# Real Estate Data Cleaning with MySQL
**Comprehensive data quality improvement pipeline for Nashville housing dataset**

## 🎯 Project Overview
Systematic data cleaning operations on real estate dataset using MySQL to demonstrate SQL data preprocessing skills and improve data quality for downstream analysis.

## 🔧 Data Quality Issues Addressed
- **Date Standardization:** Converted inconsistent date formats to uniform YYYY-MM-DD structure
- **Address Normalization:** Filled missing property addresses using available records
- **Address Parsing:** Split combined address strings into structured components (Address, City)  
- **Owner Information:** Separated owner addresses into Address, City, State columns
- **Categorical Cleanup:** Standardized 'Y'/'N' values to 'Yes'/'No' in Sold As Vacant field
- **Duplicate Removal:** Identified and eliminated duplicate records
- **Schema Optimization:** Removed unused columns for cleaner dataset structure

## 📊 Dataset Details
- **Source:** Nashville Housing dataset
- **Records:** Multiple property transactions with ownership details
- **Cleaning Operations:** 6 major data quality improvements implemented

## 🛠️ Technical Implementation
**Database:** MySQL  
**Language:** SQL with DDL/DML operations  
**Techniques:** String manipulation, joins, conditional updates, duplicate detection

## 📁 Repository Contents
- `Nashville Housing Data for Data Cleaning.csv` - Original dataset
- `Nashville Housing Data for Data Cleaning_SQL.sql` - Complete SQL cleaning script
- `README.md` - Project documentation

## 🎓 Learning Outcomes
- Hands-on experience with real-world messy data
- SQL data transformation and quality improvement techniques
- Database schema design and optimization
- Systematic approach to data preprocessing challenges
