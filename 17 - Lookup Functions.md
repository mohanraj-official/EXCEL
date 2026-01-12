# Excel Lookup Functions Reference

## Lookup Functions Overview

| Function | Exact Syntax | Purpose (What it does) | Direction |
|---------|--------------|------------------------|-----------|
| VLOOKUP | =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup]) | Searches for a value in the first column of a table and returns a value from a specified column in the same row. | Vertical, top to bottom |
| HLOOKUP | =HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup]) | Searches for a value in the top row of a table and returns a value from a specified row in the same column. | Horizontal, left to right |
| XLOOKUP | =XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode]) | Searches a range for a value and returns the matching result from another range. | Any direction |
| LOOKUP | =LOOKUP(lookup_value, lookup_vector, result_vector) | Looks up a value in a one-row or one-column range and returns a value from the same position in another range. | Vector based |
| MATCH | =MATCH(lookup_value, lookup_array, [match_type]) | Finds the position number of a value in a range. | Position finder |
| INDEX | =INDEX(array, row_num, [column_num]) | Returns a value from a table based on row and column numbers. | Value retriever |
| INDEX-MATCH | =INDEX(return_range, MATCH(lookup_value, lookup_range, 0)) | Combines position finding and value retrieval to perform flexible lookups, including left lookups. | Dynamic lookup |

---

## Detailed Component Breakdown

### VLOOKUP

- lookup_value  
  The value you want to search for, such as an employee ID.

- table_array  
  The full data table that contains the lookup column and result columns.

- col_index_num  
  The column number from which the result should be returned.

- range_lookup  
  Use FALSE or 0 to force an exact match.

---

### XLOOKUP

- lookup_array  
  The column or row containing lookup values.

- return_array  
  The column or row containing the result values.

- if_not_found  
  A custom message shown when the value is not found.

---

### INDEX and MATCH

- MATCH identifies the position of a value in a range.
- INDEX returns the value from a specific position.
- This combination supports left lookups and is stable even if columns are rearranged.

---

## Real-World Student Exercise: The Master Inventory

### Input Data (Sheet 1: Inventory)

| SKU_ID | Product_Name | Price | Stock |
|------|--------------|-------|-------|
| A-01 | Laptop | 1200 | 15 |
| B-02 | Mouse | 25 | 100 |

### Task Instructions (Sheet 2: Invoice)

1. Enter SKU ID B-02 in cell A1.
2. Display the product name in cell B1 by referencing the inventory table.
3. Display the price in cell C1 by referencing the inventory table.
4. Ensure the formula returns a clear message if the SKU does not exist.

---

## Learning Outcomes for Students

- Understand vertical and horizontal data searches.
- Handle missing values cleanly.
- Perform left-side lookups.
- Build interview-ready lookup logic.
- Reduce dependency on rigid column structures.






<BR>
<BR>

[DOWNLOAD DATASET HERE](../EXCEL/ASSETS/SCHOOL%20DATABASE.txt)

## Easy Level – Basic Lookup Understanding

| Question No | Scenario-Based Question |
|------------|-------------------------|
| 1 | Retrieve the student name for the ID STU-105 from the master student database. |
| 2 | Fetch the parent contact number for each student listed in the exam results sheet using the master data. |
| 3 | Explain why an exact match is required when searching for student IDs like STU-110. |
| 4 | Determine the column position needed to fetch the house color when the data range starts from column A. |
| 5 | Identify which lookup approach is suitable if student data is arranged horizontally instead of vertically. |
| 6 | Pull the date of birth for STU-120 from the master sheet. |
| 7 | Display the gender for STU-135 using a single lookup formula. |
| 8 | Fetch the house color for all students listed in a sports allocation sheet. |

---

## Medium Level – Error Handling and Modern Lookups

| Question No | Scenario-Based Question |
|------------|-------------------------|
| 9 | Retrieve the gender of STU-110 using a modern lookup method that works in any direction. |
| 10 | Display “Student Not Found” when an entered student ID does not exist in the master database. |
| 11 | Ensure a custom message appears instead of an error when an invalid ID is entered. |
| 12 | Return both student name and gender at the same time for a given student ID. |
| 13 | Leave the result cell blank when house color lookup fails due to missing data. |
| 14 | Pull parent contact details while safely handling missing IDs. |
| 15 | Retrieve student house color even if columns are rearranged in the master sheet. |
| 16 | Fetch student details using a lookup method that does not break when new columns are inserted. |

---

## Hard Level – Advanced and Interview Scenarios

| Question No | Scenario-Based Question |
|------------|-------------------------|
| 17 | Explain why a traditional lookup fails when the ID column is moved to the right of the student name. |
| 18 | Retrieve a student name even when the lookup column appears after the result column. |
| 19 | Identify the row position of STU-107 in the master database. |
| 20 | Return the value stored at the intersection of the 10th row and 2nd column of the dataset. |
| 21 | Build a two-way lookup where both student ID and column name are user inputs. |
| 22 | Search the student database starting from the most recent record instead of the first. |
| 23 | Find a student when only a partial student ID is known. |
| 24 | Count how many entered student IDs are missing from the master data list. |
| 25 | Retrieve house color and then display a custom instruction based on the returned value. |

---

## Empty Table Template – Data Extraction Sheet  

| Student_ID | Student_Name | Gender | Date_of_Birth | Parent_Contact | House_Color | Remarks |
|-----------|--------------|--------|---------------|----------------|-------------|---------|
|           |              |        |               |                |             |         |
|           |              |        |               |                |             |         |
|           |              |        |               |                |             |         |
|           |              |        |               |                |             |         |
|           |              |        |               |                |             |         |

