# Excel-Assignment-III
# Insurance Dataset Analysis

## Dataset
The dataset for this analysis can be found [here](https://docs.google.com/spreadsheets/d/1YwWga2LF099MVEGzbM8d2QjP90DD-CuqH2Hlw8GpRcQ/edit#gid=0). Please make a copy of the file to your local machine for analysis.

## Assignment 1

### Pre-requisites
- MS Excel
- Insurance.xlsx

### Scenario
You are given an Excel file containing insurance premiums for multiple customers.

### Tasks
1. Create a new column called Total Insured, which contains the total number of people covered under each policy. 
2. Calculate the premium paid per head by dividing the Expense column and the Total Insured column.

### What I've Done
- Added a new column Total Insured using the formula `=SUM(B2:D2)` to calculate the total number of insured people for each policy.
- Calculated the premium paid per head using the formula `=E2/C2` to divide the Expense column by the Total Insured column.

## Assignment 2

### Pre-requisites
- MS Excel
- Insurance.xlsx

### Scenario
You are given an Excel file containing insurance premiums for multiple customers.

### Tasks
1. Ensure that the Age of customers lies between 18 – 80.
2. Ensure that the gender column contains one of male, female, and others.
3. Ensure that the BMI and expenses columns contain positive values.
4. Ensure that the smoker column contains either a yes or a no.

### What I've Done
- Applied data validation to the Age column to allow values between 18 and 80.
- Applied data validation to the gender column to restrict values to male, female, and others.
- Applied data validation to the BMI and expenses columns to allow only positive values.
- Applied data validation to the smoker column to restrict values to yes or no.

## Assignment 3

### Pre-requisites
- MS Excel
- Insurance.xlsx

### Scenario
You are given an Excel file containing insurance premiums for multiple customers.

### Tasks
1. Create a dashboard that contains the following charts:
   - Line chart depicting the relation between the average premium per head and age.
   - Bar chart containing the fraction of male and female population who smoke.
   - Pie chart depicting the count of people who smoke in each region.

### What I've Done
- Created a line chart showing the relationship between the average premium per head and age.
- Created a bar chart showing the fraction of male and female population who smoke.
- Created a pie chart showing the count of people who smoke in each region.

