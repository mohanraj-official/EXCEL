# Excel Text Functions – Quick Reference

<BR>


| Function   | Exact Syntax                                   | Purpose (What it does)                                      | Real-World Use Case                                                |
|------------|-----------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------------|
| UPPER      | =UPPER(text)                                  | Converts all characters in a string to uppercase.           | Standardizing country codes, turning "usa" into "USA".             |
| LOWER      | =LOWER(text)                                  | Converts all characters in a string to lowercase.           | Creating uniform email addresses for system imports.               |
| PROPER     | =PROPER(text)                                 | Capitalizes the first letter of each word.                  | Fixing names, "john doe" becomes "John Doe".                       |
| LEFT       | =LEFT(text, [num_chars])                      | Extracts characters from the beginning of a string.         | Extracting area codes from a 10-digit phone number.                |
| RIGHT      | =RIGHT(text, [num_chars])                     | Extracts characters from the end of a string.               | Pulling the last four digits of a credit card or SSN.              |
| MID        | =MID(text, start_num, num_chars)              | Extracts characters from the middle of a string.            | Extracting digits from a product SKU like ABC-123-XYZ.             |
| CONCAT     | =CONCAT(text1, [text2], ...)                  | Joins two or more text values into one.                     | Combining first name and last name into a full name.               |
| TRIM       | =TRIM(text)                                   | Removes extra spaces except single spaces between words.    | Cleaning copied web data with unwanted spaces.                     |
| LEN        | =LEN(text)                                    | Returns the total number of characters including spaces.    | Validating password or ID length.                                  |
| SUBSTITUTE | =SUBSTITUTE(text, old, new, [instance])       | Replaces specific text with new text.                       | Updating year values in project titles.                            |
| FIND       | =FIND(find_text, within_text, [start_num])    | Returns the position of a character. Case-sensitive.        | Finding the @ symbol position in an email address.                 |
| REPLACE    | =REPLACE(old_text, start, num_chars, new_text)| Replaces text based on a given position.                    | Masking sensitive data like account numbers.                       |
| TEXT       | =TEXT(value, format_code)                     | Converts numbers or dates into formatted text.              | Displaying dates as day names like "Thursday".                     |
| CHAR       | =CHAR(number)                                 | Returns the character for a given code number.              | Adding a line break using CHAR(10) inside a formula.               |



<br>

[Download Raw Dataset](../EXCEL/ASSETS/messy_employee_dataset_text.txt)



# Excel Text Functions – Practice Questions

## Level 1: Easy (Foundational Cleaning)

| No. | Task Description |
|----|------------------|
| 1 | Convert all values in the FullName column to uppercase for a formal report. |
| 2 | Convert all values in the Email_Address column to lowercase to maintain consistency. |
| 3 | Fix the FullName column so only the first letter of each word is capitalized. |
| 4 | Calculate the length of each Department_Code and verify whether all codes have the same length. |
| 5 | Remove leading and trailing spaces from the FullName column. |
| 6 | Extract the first three characters from the Department_Code to identify the department initials. |
| 7 | Extract the last four characters from the Department_Code to identify the year. |
| 8 | Create a text string that displays the label “Employee:” followed by the FullName. |

## Level 2: Medium (Data Extraction and Formatting)

| No. | Task Description |
|----|------------------|
| 9 | Replace all underscores in the FullName column with spaces. |
|10 | Extract the three-letter role code from the middle of the Department_Code. |
|11 | Identify the position of the “@” symbol in the Email_Address. |
|12 | Clean the FullName by removing extra spaces and correcting capitalization using a single formula. |
|13 | Convert the JoinDate_Raw column to display the day name only. |
|14 | Update the year value in the Department_Code from 2024 to 2025 for all records. |
|15 | Extract the username from the Email_Address, keeping only the text before the “@” symbol. |
|16 | Extract the domain name from the Email_Address, keeping only the text after the “@” symbol. |
|17 | Display the FullName on the first line and the Department_Code on the second line within the same cell. |

## Level 3: Hard (Complex Logic and Interview Style)

| No. | Task Description |
|----|------------------|
|18 | Mask email addresses so only the first two characters and the domain remain visible. |
|19 | Generate a unique employee ID using the first two letters of the name, the last two digits of the year from the Department_Code, and the EmployeeID. |
|20 | If the Department_Code contains the text “MKT”, replace it with “MARKETING”; otherwise, keep the original value. |
|21 | Extract the text located between the underscore and the hyphen in the Department_Code. |
|22 | Clean the FullName column by removing both extra spaces and underscores. |
|23 | Identify which FullName values exceed 15 characters after cleaning. |
|24 | Check whether an email address belongs to the company domain and label it as “Internal” or “External”. |
|25 | Swap the first name and last name in the FullName column, assuming a single space separates them. |



<BR>
<BR>

[Download Raw Dataset](../EXCEL/ASSETS/SPORTS_PLAYERS_TEXT_FUNCTIONS.txt)

<BR>

# 25 Interview-Style Questions – Cricket Analytics Scenario

## Level 1: Easy (Cleanup and Basic Extraction)

| No. | Scenario-Based Question |
|----|--------------------------|
| 1 | The official scoreboard needs professional formatting. Update all Player_Identity values so each word starts with a capital letter. |
| 2 | Social media links are breaking in reports. Standardize all Social_Handle values so they appear in lowercase. |
| 3 | Some player names fail during lookups. Remove hidden leading and trailing spaces from the Player_Identity column. |
| 4 | Analysts need a quick country identifier. Extract the first three characters from Team_Region to get the country code. |
| 5 | The management team wants debut insights. Extract the last four characters from Team_Region to identify the debut year. |
| 6 | Data quality checks are required. Calculate the character length of Career_Stat_Code and verify consistency across records. |
| 7 | The database requires uniform codes. Convert all Team_Region values into uppercase format. |
| 8 | Create a readable identifier by joining Player_Identity and Team_Region with a hyphen in between. |

## Level 2: Medium (Data Transformation)

| No. | Scenario-Based Question |
|----|--------------------------|
| 9 | Performance analysis requires role identification. Extract the role code from the middle of the Team_Region value. |
|10 | Stat analysis is delayed due to text labels. Remove the label text from Career_Stat_Code so only numeric values remain. |
|11 | Name formatting is inconsistent. Replace all underscores in Player_Identity with single spaces. |
|12 | Structural analysis is required. Identify the position of the hyphen within the Team_Region value. |
|13 | Handles must follow platform rules. Remove the leading symbol from Social_Handle values while keeping the rest intact. |
|14 | Security policies require masking. Hide the middle character(s) of Player_ID while keeping the first and last characters visible. |
|15 | Reports need a decade view. Convert the debut year into a decade format such as “2000s”. |
|16 | Handle structure validation is required. Identify where the player name ends within the Social_Handle value. |
|17 | Profile cards need better readability. Display the player name on the first line and career stats on the second line in one cell. |

## Level 3: Hard (Advanced Business Logic)

| No. | Scenario-Based Question |
|----|--------------------------|
|18 | Numeric analysis fails due to text formatting. Extract the run value from Career_Stat_Code and ensure it behaves as a number. |
|19 | Data cleanup must be automated. Convert the value “  virat_KOHLI  ” into a clean and properly formatted player name using one formula. |
|20 | Role naming varies by length. Extract the text located between the country code and debut year in Team_Region dynamically. |
|21 | Marketing needs contact details. Generate a fake email using the first three letters of the player name, last three letters of the team, and a fixed domain. |
|22 | Player branding analysis is required. Check whether the Social_Handle contains the word “finisher” and classify the player accordingly. |
|23 | Data integrity checks reveal anomalies. Identify and clean career stats that contain leading zeros in the numeric portion. |
|24 | Broadcasting requires a new display format. Convert names like “Virat Kohli” into “Kohli, V.” |
|25 | Role auditing is requested. Extract only the text located between the first underscore and the first hyphen in Team_Region. |

