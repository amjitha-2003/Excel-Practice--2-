# Excel Practice-1

## Montgomery_Fleet_Equipment_Inventory_FA

## INTRODUCTION
This project demonstrates my work as a Junior Data Analyst using real-world fleet inventory data from a local government office. This practice was completed in in two parts:
> PART 1 :- Data Cleaning and Preparation
                 Ensuring the dataset is accurate, complete, and well-formatted for analysis. This includes identifying and fixing common data quality issues, such as missing values, duplicates, and inconsistent formatting.

> PART 2 :- Data Analysis with Pivot Tables
                 Uncovering insights about equipment usage and departmental distribution. These analyses will form the foundation for future data visualizations and reporting.

## OBJECTIVES
> Clean and organize the fleet inventory dataset using **Excel for the web**.

> Identify and handle **missing values and duplicate records**.

> Correct inconsistent **formatting and data entries**.

> Prepare the dataset for accurate and reliable analysis.

> Create **Pivot Tables** to analyze equipment usage and departmental distribution.

> Identify useful **patterns and insights** from the cleaned data.

> Strengthen practical skill in **Excel, data cleaning, and data analysis**.

FILES INCLUDED :
* Raw Data part 1 (Used for Part 1)
* Raw Data part 2 (Used for Part 2)
* Part 1 (Data cleaned and formatted)
* Part 2 (Data analysis with Pivot table)

## PART 1 :-
This practice project is based on a scenario where a Junior Data Analyst works with fleet inventory data from a local government office. The data was provided in CSV format and required cleaning and preparation before analysis.

<img width="1527" height="812" alt="image" src="https://github.com/user-attachments/assets/f97a67c8-f472-408b-9f31-1448378db92b" />

                                                   Raw data used in Part1 


#### **The dataset used in this lab comes from the following source:** 
https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr under a Public Domain license.

> ### *STEP  1 - Save the CSV file as an XLSX file*
* Change the ‘Viewing’ in the ToolTip to ‘Editing’inorder to save the file as an XLSX file.
* The file is converted when you click ‘Convert’ in the prompt.

<img width="1090" height="537" alt="image" src="https://github.com/user-attachments/assets/02c79fb1-d645-4ed0-af16-80bede73ff50" />

<img width="1090" height="418" alt="image" src="https://github.com/user-attachments/assets/8e47005b-be2a-4b1a-876e-59f027a60124" />

> ### *STEP  2 - Column widths*
* Sort out the widths of all columns so that the data is clearly visible in all cells.

> ### *STEP  3 - Empty rows*
* Use the Filter feature to look for blanks and remove all empty rows from the data.

> ### *STEP  4 - Duplicate records*
* Use either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data. 

> ### *STEP  5 - Spelling*
* The original source file data has not been checked for errors in the spelling. Check for spelling mistakes in the data and fix them.

> ### *STEP  6 - Whitespace*
* Use the Find and Replace feature to remove all double-spaces from the data.

> ### *STEP  7 - Department names*
* When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now split over two columns in the data. Use Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.

<img width="1532" height="813" alt="image" src="https://github.com/user-attachments/assets/b4a73e0d-23e6-432b-9ae6-d4aa4a2f1aab" />

                                                        Cleaned Data

## PART 2 :-
I used the previously cleaned fleet inventory data to perform data analysis using Excel for the web. I created Pivot Tables to examine equipment usage, departmental distribution, equipment classes, and inventory counts. The analysis helped identify patterns and summarize key findings that can be used for future dashboard visualizations and reporting.

<img width="1531" height="813" alt="image" src="https://github.com/user-attachments/assets/7895f90e-9bea-44d1-a7e0-9558405e7eb7" />

                                                   Data used for Part 2

> ### *STEP  1 - Format the data as a table*
* Use the Format as Table option to format the data as a table.

> ### *STEP  2 - Use AutoSum to calculate values*
* Use AutoSum to find the following values for column ‘C’ and record each of the values:
>> SUM

>> AVERAGE

>> MINIMUM

>> MAXIMUM

>> COUNT

> ### *STEP  3 - Create a Pivot Table*
* Create a new worksheet and name it Pivot Table 1.
* Use the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.

> ### *STEP  4 - Sort the pivot table data*
* Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.

> ### *STEP  5 - Make two more pivot tables exactly the same as task 3*
* Create two new worksheets named Pivot Table 2 and Pivot Table 3.
* Follow the same steps you performed in Tasks 3 and 4 to create two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.

> ### *STEP  6 - Analyze data in the pivot table*
Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:
* In Pivot Table 2 add the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.
* Collapse all fields except the top one - Transportation.
* In Pivot Table 3 add the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.
* Collapse all fields except the top one - CUV.
* Ensure the worksheets are arranged in the following order in the workbook:

 **Montgomery_Fleet_Equipment_Inventory**, followed by **Pivot Table 1**, **Pivot Table 2**, and **Pivot Table 3**.



