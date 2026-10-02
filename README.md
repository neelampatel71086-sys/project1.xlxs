# project1.xlxs
Employee Salary Excel Dataset
Overview

This dataset contains employee information along with salary-related calculations using Excel's ROUND, CEILING, and FLOOR functions.

The dataset includes 20 employees and the following fields:

Employee ID

Name

Department

Salary

Joining Date

ROUND

CEILING

FLOOR

Dataset Structure
Column	Description
Employee ID	Unique identification number for each employee
Name	Employee name
Department	Employee's department
Salary	Employee's salary
Joining Date	Date the employee joined the organization
ROUND	Salary rounded to the nearest whole number
CEILING	Salary rounded upward to the nearest multiple of 5
FLOOR	Salary rounded downward to the nearest multiple of 5
Excel Functions Used
ROUND

The ROUND function rounds a number to a specified number of digits.

Formula:

=ROUND(D2,0)


Example:

Salary: 86766
ROUND: 86766

CEILING

The CEILING function rounds a number upward to the nearest specified multiple.

Formula:

=CEILING(D2,5)


Example:

Salary: 31943
CEILING: 31945

FLOOR

The FLOOR function rounds a number downward to the nearest specified multiple.

Formula:

=FLOOR(D2,5)


Example:

Salary: 31943
FLOOR: 31940

Important Note

The original CEILING values in the dataset appear to use a different rule in several rows. If the intended requirement is to round salaries upward to the nearest multiple of 5, the correct formula is:

=CEILING(D2,5)


Similarly, for rounding downward to the nearest multiple of 5:

=FLOOR(D2,5)

Example

For an employee with a salary of 54,149:

Calculation	Result
Salary	54,149
ROUND	54,149
CEILING	54,150
FLOOR	54,145
Dataset Statistics

Total Employees: 20

Departments: Finance, HR, IT, Marketing

Salary Range: ₹31,943 – ₹116,284

Purpose: Excel function practice and data analysis

Learning Objectives

This dataset can be used to practice:

Working with employee datasets in Excel.

Applying mathematical functions.

Understanding rounding behavior.

Using ROUND, CEILING, and FLOOR.

Comparing original values with calculated values.

Identifying and correcting formula errors.

Performing basic employee salary analysis.

Recommended Excel Formulas

Assuming Salary is in column D and the first employee is in row 2:

=ROUND(D2,0)

=CEILING(D2,5)

=FLOOR(D2,5)


Copy each formula down through row 21 to calculate the values for all 20 employees.

File Usage

This dataset is suitable for:

Excel practice

Data analysis exercises

Formula demonstrations

Spreadsheet assignments

Learning rounding functions

Beginner-level data manipulation

License

This dataset is intended for educational and practice purposes.
