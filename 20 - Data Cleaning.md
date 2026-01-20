## Data Cleaning – Simple Explanation

### What is Data Cleaning

* Data cleaning means fixing or removing wrong data.
* It handles incorrect, duplicate, incomplete, or badly formatted data.
* In real jobs, analysts spend around 80 percent of their time cleaning data before analysis.

---

## 1. Core Tools Overview

* Removing Duplicates

  * Deletes repeated rows.
  * Ensures each record is unique.

* Text to Columns

  * Splits one cell into multiple cells.
  * Uses separators like comma, space, or hyphen.
  * Example

    * John,Doe becomes

      * John
      * Doe

* TRIM function

  * Removes extra spaces.
  * Keeps only one space between words.

* CLEAN function

  * Removes hidden or non-printable characters.
  * Common in data copied from old systems or websites.

---

## 2. Cleaning Techniques

### A. Text Cleaning

* Basic

  * Use Find and Replace (Ctrl + H).
  * Removes unwanted words or symbols.

* Intermediate

  * Use TRIM with PROPER.
  * Fixes spacing and capitalization together.

* Advanced

  * Use Flash Fill (Ctrl + E).
  * Extracts patterns automatically.
  * Example

    * Extracting middle names from a large list.

---

### B. Number Cleaning

* Basic

  * Change Number Format.
  * Removes currency symbols or extra decimals.

* Intermediate

  * Use Paste Special and Multiply by 1.
  * Converts numbers stored as text into real numbers.

* Advanced

  * Use VALUE or ABS.
  * Fixes apostrophes or wrong negative signs.

---

### C. Date Cleaning

* Basic

  * Change format from General to Short Date.
  * Checks if Excel recognizes the date.

* Intermediate

  * Use Text to Columns.
  * Select correct date format like YMD or DMY.

* Advanced

  * Use DATEVALUE to convert text dates.
  * Use DATE function to combine year, month, and day columns.

---

## 3. Real-World Dirty Data Problems

* Web data

  * Problem

    * Hidden spaces in text.
  * Fix

    * =TRIM(CLEAN(A1))

* Old systems

  * Problem

    * Dates like 20260120.
  * Fix

    * Text to Columns
    * Fixed Width
    * Date format YMD

* Manual typing

  * Problem

    * USA, U.S.A, usa.
  * Fix

    * Remove Duplicates
    * Find and Replace

---

## 4. Student Task: Data Scrubbing Challenge

Dataset

* 50 customer records.
* Names have extra spaces.
* Phone numbers have hyphens.
* Dates are stored as text.

Tasks

* Task 1

  * Use TRIM on Customer Name.

* Task 2

  * Use Text to Columns.
  * Split City-State into two columns.

* Task 3

  * Use Remove Duplicates.
  * Ensure CustomerID is unique.

* Task 4

  * Use SUBSTITUTE.
  * Remove hyphens from phone numbers.





<BR>
<BR>

[DOWNLOAD THE DATASET](../EXCEL/ASSETS/dirty%20dataset.txt)

<BR>

| S.No | Phase                                 | Task Details                               |
| ---- | ------------------------------------- | ------------------------------------------ |
| 1    | Deduplication                         | Use Remove Duplicates                      |
|      |                                       | Base it on the ID column                   |
|      |                                       | Rows 1 and 3 are identical                 |
|      |                                       | Rows 12 and 20 are identical               |
| 2    | Text Standardization – Basic          | Remove special characters                  |
|      |                                       | Use Find and Replace (Ctrl + H)            |
|      |                                       | Delete opening and closing parentheses ( ) |
|      |                                       | Apply on Contact_Info column               |
|      |                                       | Split data                                 |
|      |                                       | Use Text to Columns                        |
|      |                                       | Column: Region_Code                        |
|      |                                       | Delimiter: hyphen or underscore            |
|      |                                       | Output: Region and Office City             |
| 3    | Formula-Based Cleaning – Intermediate | Fix names                                  |
|      |                                       | Create a new column                        |
|      |                                       | Formula: =PROPER(TRIM(CLEAN(B2)))          |
|      |                                       | Converts mary JANE to Mary Jane            |
|      |                                       | Removes hidden characters                  |
|      |                                       | Normalize contact data                     |
|      |                                       | Use SUBSTITUTE                             |
|      |                                       | Remove dots and spaces                     |
|      |                                       | Keep only numbers and hyphens              |
| 4    | Numeric and Date Fixing – Advanced    | Fix numbers stored as text                 |
|      |                                       | Amount_Sold Row 9 shows '1100              |
|      |                                       | Select the column                          |
|      |                                       | Use Error Trace dropdown                   |
|      |                                       | Convert to Number                          |
|      |                                       | Handle calculation errors                  |
|      |                                       | Use IFERROR                                |
|      |                                       | Replace #VALUE! with 0 in Amount_Sold      |
|      |                                       | Repair dates                               |
|      |                                       | Dates use different separators             |
|      |                                       | Select Order_Date column                   |
|      |                                       | Text to Columns                            |
|      |                                       | Next. Next                                 |
|      |                                       | Select Date as DMY                         |
|      |                                       | Finish                                     |
