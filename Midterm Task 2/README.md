# Midterm Lab Task 2 - Data Cleaning and Transformation Using Power Query Editor
For this task we are given an UnclenedDSJObs csv taken from a Job Posting site available in Kaggle (See rawfile) and we are Task to perform Data Transformation Using Power Query Editor to focus on the following:
- Which Job Roles pay the highest and least
- What size companies pay the best
- Where Job Roles or Job Titles pay the best and least in a specific state

## Step 1 - Data Cleaning process
- Remove All the characters after the ( open parentheses
- Created 2 New Columns (From the Salary Estimate) Min Sal and Max Sal
- Added Column – Role Type
- Split Location into 2 columns, City and State
- Filtered and removed incorrect location
- Changed values of all-1, 0, and blanks to others
- Cleaned Company name and remove Rates after the name of company
- Removed Column Descriptions

## Step 2 - Reshape and Group the Tables
- Created a duplicate of the cleaned file and named Sal By Role Type dup
- Created a reference of the cleaned file and named Sal By Role Size ref
- Mapped other files to include the full name of the state instead of the abbreviation
- Created a reference of the cleaned file and named Sal By State ref

## STEP 3 Here's the screenshot of my output before I started data cleaning (See screenshot)
![screenshot](https://github.com/barbieminion/EDM-Portfolio/blob/main/Midterm%20Task%202/images/Before%20Transformation.png)

## STEP 4 Here's the screenshot of my output after I started data cleaning and transformation (See screenshot)
![screenshot](https://github.com/barbieminion/EDM-Portfolio/blob/main/Midterm%20Task%202/images/Cleaned%20File.png)

## Here are the screenshots of all queries
![screenshot](https://github.com/barbieminion/EDM-Portfolio/blob/main/Midterm%20Task%202/images/Sal%20by%20Company%20Size.png)
![screenshot](https://github.com/barbieminion/EDM-Portfolio/blob/main/Midterm%20Task%202/images/Sal%20by%20Role%20Type.png)
![screenshot](https://github.com/barbieminion/EDM-Portfolio/blob/main/Midterm%20Task%202/images/Sal%20by%20State%20ref.png)

## Here is the Completed File
[Finished Data Transformation](https://github.com/barbieminion/EDM-Portfolio/blob/main/Midterm%20Task%202/Finished%20Data%20Transformation%20-%20Dana%20Mae%20Carbonel.xlsx)
