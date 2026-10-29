# Module-End-Assignment---Excel
This project focuses on healthcare data analysis and insights using Excel. It involves Data Cleaning, Data Transformation, exploration and visualization and dashboard creation for analyse health conditions and charges.
What I Did,
1. Data Cleaning
-Identified missing values marked with '?' and replaced them with appropriate values using the Find and Replace method.
-Filled missing values in the 'Year' column with the average of available year values and rounded to the nearest integer.
-Filled missing values in the 'Hospital Tier', 'City Tier' and 'Smoker ' Column in the “Medical Examinations” Table and "Hospitalization Details" Table
with the most occurring values in their respective columns.
-Filled missing values in the state ID column with "Unknown".

3. Data Transformation
-Split the 'Names' column into Title, First Name, and Last Name in the “Customer Names” Table using the Text to Columns method.
-Corrected the inconsistencies in the  'Heart Issues' and 'Smoker' column with the Find and Replace method.
-Converted non-numerical values in the 'Number Of Major Surgeries' column to numerical values using the Find and Replace method.
-Categorized BMI values into different weight status groups using "IFS" Function.
-Categorized HbA1C values into diabetes status groups using "IFS" Function.
-Combined date, month and Year columns to create the Date of Birth column using "CONCATENATE" Function.
-Calculated the age of each customer using "DATEDIF" Function based on their date of birth and using data collection date with "08 June 2023".
-Formatted healthcare charges as currency($).

4. Data Exploration, Analysis and Visualization
-Combined three sheets into a single sheet named 'Healthcare'using VLOOKUP Function and Customer ID as the common column.
-Created PivotTables and Pivot charts for healthcare data analysis and insights.

5. Dashboard Creation
-Created an interactive dashboard to present key insights.
-Added slicers for 'Weight Status' and 'Diabetes Status' for comparison of health outcomes and charges based on body 
 weight and diabetes condition.
-Added KPI indicators for total healthcare Charges and total number of customers.





- Added KPI indicators for total healthcare Charges and total number of customers.

