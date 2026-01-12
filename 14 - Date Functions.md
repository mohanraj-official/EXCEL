





# Module 14 – Date Functions

| Function  | Exact Syntax | What It Does | Real-World Use Case |
|----------|--------------|--------------|---------------------|
| TODAY | =TODAY() | Returns the current date. Updates automatically. | Showing today’s date in reports like daily sales or attendance tracking. |
| NOW | =NOW() | Returns the current date and time. Updates automatically. | Tracking the exact timestamp when a report was last refreshed. |
| DATE | =DATE(year, month, day) | Creates a valid date from year, month, and day values. | Building dates from separate columns like Year, Month, and Day. |
| DAY | =DAY(date) | Extracts the day number from a date. | Finding the day of the month when an employee joined. |
| MONTH | =MONTH(date) | Extracts the month number from a date. | Grouping sales data by month. |
| YEAR | =YEAR(date) | Extracts the year from a date. | Analyzing data year-wise for trends or growth. |
| WEEKDAY | =WEEKDAY(date, [return_type]) | Returns the day of the week as a number. | Checking whether a date falls on a weekday or weekend. |
| WEEKNUM | =WEEKNUM(date, [return_type]) | Returns the week number of the year. | Weekly performance or payroll analysis. |
| EDATE | =EDATE(start_date, months) | Shifts a date by a given number of months. | Calculating contract renewal dates or EMI schedules. |
| EOMONTH | =EOMONTH(start_date, months) | Returns the last date of a month after shifting months. | Finding month-end closing dates for accounting. |
| WORKDAY | =WORKDAY(start_date, days, [holidays]) | Returns a date after excluding weekends and holidays. | Calculating project deadlines or delivery dates. |
| DAYS | =DAYS(end_date, start_date) | Returns the number of days between two dates. | Measuring total days between order and delivery. |
| DATEDIF | =DATEDIF(start_date, end_date, unit) | Calculates difference between dates in days, months, or years. | Calculating employee experience or age. |



<br>
<br>

[DOWNLOAD THE DATASET](../EXCEL/ASSETS/hotel%20dataset_datefunctions.txt)

# Interview Questions – Date Functions (Scenario-Based)

## Level 1: Easy (Date Basics and Understanding)

| No. | Scenario-Based Question |
|----|--------------------------|
| 1 | Display today’s date automatically on a daily operations report. |
| 2 | Show the current date and time to track when a dashboard was last refreshed. |
| 3 | Create a valid date using separate Year, Month, and Day columns. |
| 4 | Extract only the day number from each check-in date. |
| 5 | Extract the month number from booking dates for monthly grouping. |
| 6 | Extract the year from booking dates for yearly analysis. |
| 7 | Identify which day of the week each booking was made. |
| 8 | Determine whether a booking date falls on a weekday or weekend. |
| 9 | Display the week number for each booking date. |

## Level 2: Medium (Business Analysis and Date Calculations)

| No. | Scenario-Based Question |
|----|--------------------------|
|10 | Calculate the number of days between check-in and check-out dates. |
|11 | Identify bookings that happened within the same week. |
|12 | Calculate the booking date that falls exactly three months after check-in. |
|13 | Find the last date of the month for each check-in date. |
|14 | Determine the expected checkout date after adding working days only. |
|15 | Identify bookings that occur at the end of a month. |
|16 | Create a report that shows month-wise booking counts. |
|17 | Calculate how many days remain between today and the check-in date. |

## Level 3: Hard (Interview and Real-World Logic)

| No. | Scenario-Based Question |
|----|--------------------------|
|18 | Calculate the total number of completed days between check-in and check-out, ignoring partial months. |
|19 | Identify customers whose stay duration exceeds the average stay length. |
|20 | Determine customer stay duration in years, months, and days separately. |
|21 | Flag bookings that span across two different months. |
|22 | Calculate the customer’s experience in full years based on their first booking date. |
|23 | Identify bookings made during the last week of the year. |
|24 | Determine the next working day after the checkout date, excluding weekends and holidays. |
|25 | Classify bookings as “Short Stay” or “Long Stay” based on the number of days stayed. |


<BR>
<BR>


[DOWNLOAD THE DATASET](../EXCEL/ASSETS/ZOHO%20EMPLOYEE%20DETAILS.txt)

# Interview Questions – Date Functions Only (Zoho Employee Dataset)

## Level 1: Easy (Date Understanding and Basics)

| No. | Scenario-Based Question |
|----|--------------------------|
| 1 | Display today’s date automatically on the HR dashboard. |
| 2 | Show the current date and time to track when the employee report was generated. |
| 3 | Extract the year from each employee’s Date_of_Joining for yearly hiring analysis. |
| 4 | Extract only the month from Date_of_Joining to study monthly hiring trends. |
| 5 | Extract the day number from Date_of_Joining for date-based grouping. |
| 6 | Identify the day of the week on which each employee joined. |
| 7 | Determine whether an employee joined on a weekday or weekend. |
| 8 | Display the week number of the year for each Date_of_Joining. |
| 9 | Create a clean joining date using separate Year, Month, and Day values. |

## Level 2: Medium (Date Calculations and Business Analysis)

| No. | Scenario-Based Question |
|----|--------------------------|
|10 | Calculate how many days each employee has worked in the company until today. |
|11 | Identify employees who completed exactly one year in the company. |
|12 | Find the joining date that falls exactly six months after an employee’s original joining date. |
|13 | Determine the last date of the joining month for each employee. |
|14 | Calculate the expected confirmation date assuming confirmation happens after 90 working days. |
|15 | Identify employees who joined at the end of a month. |
|16 | Generate a month-wise employee joining count report. |
|17 | Calculate the number of days remaining until an employee completes five years in the company. |

## Level 3: Hard (Interview and Real-World Date Logic)

| No. | Scenario-Based Question |
|----|--------------------------|
|18 | Calculate employee experience in full years, ignoring partial years. |
|19 | Calculate employee experience in years and months separately. |
|20 | Identify employees whose experience exceeds the company’s average experience. |
|21 | Flag employees who joined during the last week of any year. |
|22 | Identify employees whose joining date falls within the same calendar week. |
|23 | Calculate the next working day after an employee’s joining date, excluding weekends and holidays. |
|24 | Identify employees who joined exactly at the start of a month. |
|25 | Classify employees as “New Joiner” or “Experienced” based on a date threshold. |










