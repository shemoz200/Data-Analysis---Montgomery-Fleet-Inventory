# Data-Analysis---Montgomery-Fleet-Inventory
Fleet Inventory: Data Cleaning and Visualisation
# Project Overview \

As a newly hired Junior Data Analyst for a local government office, I was tasked with cleaning and preparing inventory data for the fleet of vehicles used by various departments. This task was crucial to ensure the data was accurate, consistent, and ready for analysis.This repository documents the steps and outcomes of cleaning, preparing, and analyzing the Montgomery Fleet Equipment Inventory data using Excel for the Web. The project is divided into two parts:

Part 1: Data Cleaning and Preparation
Part 2: Data Analysis with Pivot Tables


# The aim

This project's main objective was to clean and standardise a dataset that had been in raw, comma-separated value (CSV) format until now. This required resolving problems such uneven formatting, redundant records, and inaccurate data.

## Steps Taken

# Part 1: Data Cleaning and Preparation
Objective

To clean the raw data and prepare it for analysis by resolving common data issues, including:

- Adjusting column widths for readability.
- Removing empty rows.
- Identifying and fixing duplicate records.
- Correcting spelling errors.
- Eliminating unnecessary whitespaces.
- Merging split department names into a single column.

  # Steps Performed

Column Width Adjustment
- Ensured all data was visible by resizing the columns to fit the content.
  
Removal of Empty Rows
- Used the Filter tool to identify and delete all blank rows from the dataset.
  
Duplicate Removal
- Applied the "Remove Duplicates" tool to eliminate duplicate entries.
  
Spelling Error Correction
- Performed a manual review of the dataset to identify and fix any spelling errors.
  
Whitespace Cleanup
- Used the "Find and Replace" tool to replace double spaces with single spaces.
  
Merging Department Names
- Leveraged the Flash Fill feature to merge department names that were incorrectly split into two columns.

# Outcome

The cleaned dataset is saved as Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx. It is now formatted consistently, free of errors, and ready for analysis.

Part 2: Data Analysis with Pivot Tables
Objective

To use pivot tables for summarizing and analyzing the cleaned fleet inventory data.

# Steps Performed

Format Data as Table
- The dataset was formatted as a table to enable easier manipulation and dynamic updates.
  
AutoSum Calculations
- Calculated SUM, AVERAGE, MIN, MAX, and COUNT values for the "Equipment Count" column using the AutoSum feature.
  
Pivot Table 1: Department-Wise Summary
- Created a pivot table summarizing the Sum of Equipment Count by Department.
Sorted the table in descending order based on the equipment count.

- Pivot Table 2: Equipment Class within Departments
  
Added the Equipment Class field beneath the Department field in rows.
- Collapsed all rows except Transportation to focus the analysis.
  
Pivot Table 3: Departments within Equipment Class
- Added the Equipment Class field above the Department field in rows.
- Collapsed all rows except CUV to focus on specific equipment types.

# Outcome

The analysis revealed department-specific and equipment-class-specific trends in fleet inventory. The final workbook (Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsx) contains:

- Three pivot tables showcasing summarized data.
- Insights into the distribution of equipment across departments and equipment types.



# TOOLS USED 
Excel for the Web: Performed all tasks using the free web version of Excel.
Built-in Excel Features: Utilised features such as AutoFilter, Remove Duplicates, Flash Fill, and Find and Replace.


## Repository Structure

Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.xlsx: The original uncleaned dataset.
Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx: The cleaned and prepared dataset.
Montgomery_Fleet_Equipment_Inventory_FA_PART_2_START.xlsx:The cleaned dataset used as the starting point for pivot table creation.
Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsx: The final Excel file containing the pivot tables and analysis based on the fleet inventory data.






 
