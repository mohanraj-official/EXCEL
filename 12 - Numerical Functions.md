# Essential Excel Functions with Syntax and Use Cases

| Function | Exact Syntax | Description (What it does) | Real-World Application |
|--------|-------------|-----------------------------|------------------------|
| SUM | =SUM(range) | Adds all numbers in a range | Totaling monthly sales or expenses |
| AVERAGE | =AVERAGE(range) | Returns the arithmetic mean | Finding the average test score or temperature |
| COUNT | =COUNT(range) | Counts cells containing numbers only | Counting how many customers made a payment |
| COUNTA | =COUNTA(range) | Counts cells that are not empty | Counting total employees including names and IDs |
| COUNTBLANK | =COUNTBLANK(range) | Counts empty cells | Identifying missing data in a survey |
| MIN / MAX | =MIN(range) / =MAX(range) | Finds the lowest or highest value | Finding the cheapest product or highest salary |
| RANK | =RANK(number, ref, [order]) | Returns the rank of a number in a list | Ranking students by grades or sales reps by KPIs |
| SUMIF | =SUMIF(range, criteria, [sum_range]) | Adds values based on one condition | Totaling sales only for the East region |
| SUMIFS | =SUMIFS(sum_range, crit_range1, crit1, ...) | Adds values based on multiple conditions | Totaling sales for East region and Electronics |
| COUNTIF | =COUNTIF(range, criteria) | Counts cells based on one condition | Counting how many students passed an exam |
| COUNTIFS | =COUNTIFS(crit_range1, crit1, ...) | Counts cells based on multiple conditions | Counting male survivors over age 18 |
| AVERAGEIF | =AVERAGEIF(range, crit, [avg_range]) | Averages values based on one condition | Average salary of Manager level employees |
| AVERAGEIFS | =AVERAGEIFS(avg_range, crit_range1, crit1, ...) | Averages values based on multiple conditions | Average fare for 1st Class from Southampton |
| SUMPRODUCT | =SUMPRODUCT(array1, [array2], ...) | Multiplies arrays and sums the results | Calculating total invoice using price and quantity |
| ROUND | =ROUND(number, num_digits) | Rounds a number to specified decimals | Formatting currency in financial reports |
| ROUNDUP / ROUNDDOWN | =ROUNDUP(num, digits) / =ROUNDDOWN(num, digits) | Forces rounding up or down | Calculating number of buses required |
| RAND | =RAND() | Returns a random number between 0 and 1 | Randomizing data for audits or lotteries |
| RANDBETWEEN | =RANDBETWEEN(bottom, top) | Returns a random integer in a range | Generating random IDs or sample test data |

--


[Download Raw Dataset](../EXCEL/ASSETS/RAW%20DATASET%20FOR%20NUMERIC%20FUNCTIONS.txt)





# TITANIC DATASET QUESTIONS

---

## A. Basic Counting and Missing Data  
Functions focus: COUNT, COUNTA, COUNTBLANK

| Question No | Task |
|------------|------|
| A1 | Find the total number of passengers listed in the Name column |
| A2 | Calculate how many passengers have a numeric value in the Age column |
| A3 | Identify how many passengers are missing Age information |
| A4 | Using a single formula, calculate the percentage of missing ages compared to total passengers |
| A5 | If a new passenger is added in row 51 with only the Name filled, explain how COUNT and COUNTA behave differently |

---

## B. Logical Aggregations  
Functions focus: SUMIF, SUMIFS, COUNTIF, COUNTIFS

| Question No | Task |
|------------|------|
| B1 | Count how many passengers survived (Survived = 1) |
| B2 | Calculate the total Fare paid by passengers who embarked from C (Cherbourg) |
| B3 | Count how many Female passengers were in 3rd Class |
| B4 | Calculate the total Fare paid by Male passengers over the age of 30 |
| B5 | Count passengers who had more than one sibling or spouse (SibSp > 1) and did not survive |

---

## C. Statistics and Ranking  
Functions focus: MIN, MAX, AVERAGE, RANK, ROUND

| Question No | Task |
|------------|------|
| C1 | Find the youngest and oldest passenger ages |
| C2 | Calculate the average Fare of all 50 passengers and round it to 2 decimal places |
| C3 | Rank passengers based on Fare paid, highest fare should be Rank 1 |
| C4 | Calculate the average age of passengers in 1st Class only |
| C5 | Find the difference between the maximum Fare and the overall average Fare |

---

## D. Advanced Logic  
Functions focus: SUMPRODUCT, ROUND, RAND, RANDBETWEEN

| Question No | Task |
|------------|------|
| D1 | Use SUMPRODUCT to calculate a weighted family count using SibSp and Parch |
| D2 | Round the average Fare up to the nearest whole number |
| D3 | Round the Age of the passenger in row 2 down to zero decimal places |
| D4 | Generate a random Seat Number between 100 and 500 for each passenger |
| D5 | Create a Random Sort column using RAND to shuffle passengers |

---

## E. Comparison and Mastery  
Functions focus: AVERAGEIFS, SUMIFS, COUNTIFS, SUMPRODUCT

| Question No | Task |
|------------|------|
| E1 | Find the average Fare for Females in 1st Class who survived |
| E2 | Calculate the total SibSp for passengers whose Fare is greater than 50 |
| E3 | Count passengers whose age is between 20 and 40 inclusive |
| E4 | Find the average age of passengers who did not survive and paid a Fare less than 10 |
| E5 | Ultimate Challenge: Calculate the total Fare after rounding each Fare to the nearest whole number within the formula |




<BR><BR>

# Electronics Store Dataset Questions  
## The Business Analyst Challenge

[Download Raw Dataset](../EXCEL/ASSETS/2%20-%20ECOMMERCE%20DATA%20SET.CSV)


## Table 1: Revenue and Pricing Analysis

| No | Business Scenario | Task |
|----|------------------|------|
| 1 | Revenue Report | Calculate the total revenue generated from all transactions |
| 2 | Pricing Benchmark | Find the average unit price across the entire product catalog |
| 3 | Entry-Level Budgeting | Identify the lowest unit price among all products |
| 4 | Premium Performance | Identify the highest unit price in the dataset |
| 5 | Clean Reporting | Round the average unit price to the nearest whole number |

---

## Table 2: Order Volume and Data Quality

| No | Business Scenario | Task |
|----|------------------|------|
| 6 | Logistics Volume | Count the total number of orders processed |
| 7 | Data Integrity Check | Count how many cells in the Payment Method column contain data |
| 8 | Audit Trail | Count how many completely blank cells exist in the dataset |
| 9 | Customer Reach | Count the total number of Guest transactions |
| 10 | High-Value Threshold | Count orders with unit price higher than the overall average |

---

## Table 3: Category and Customer Insights

| No | Business Scenario | Task |
|----|------------------|------|
| 11 | Tech Segment Value | Calculate total revenue for the IT category |
| 12 | Non-IT Market | Calculate total revenue for all categories except IT |
| 13 | Bulk Audio Sales | Count Audio category orders with quantity greater than 1 |
| 14 | Wearable Trends | Calculate the average price of products in the Wearable category |
| 15 | Smart Tech Search | Count products with the word Smart in the product name |

---

## Table 4: Advanced Calculations and Logic

| No | Business Scenario | Task |
|----|------------------|------|
| 16 | Performance Competition | Rank every order based on total transaction value |
| 17 | Total Value Without Helper Column | Calculate total sales using quantity multiplied by unit price in one formula |
| 18 | Discount Floor | Calculate average revenue and round it down to the nearest whole number |
| 19 | Tax Estimation | Calculate total tax and round the final value up |
| 20 | Member Incentive | Calculate total 5 percent bonus payout for Member transactions |

---

## Table 5: Time, Randomization, and Security

| No | Business Scenario | Task |
|----|------------------|------|
| 21 | Loyalty and Finance | Calculate total revenue from Members who paid by Credit Card |
| 22 | Mobile and PayPal Efficiency | Find the average quantity of Mobile items sold using PayPal |
| 23 | Early-Month Analysis | Calculate total revenue for orders placed between January 1 and January 15 |
| 24 | Lottery Selection | Generate a random decimal number between 0 and 1 for each transaction |
| 25 | Security Codes | Generate a random 4-digit security PIN for each order |






