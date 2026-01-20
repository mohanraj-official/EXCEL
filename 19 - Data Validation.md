
# Data Validation – Summary Notes

## Definition

* Data Validation controls what a user enters into a cell.
* It ensures data integrity.
* It prevents typos, invalid dates, and incorrect entries.

---

## 1. Core Concepts

### Basic: Drop-Down List

* Displays a selectable list inside a cell.
* Forces users to choose predefined values.
* Creation path:

  * Data Tab
  * Data Validation
  * Settings
  * Allow: List
  * Source: comma-separated values or range
* Use case:

  * Avoids spelling mismatches like "MKT" vs "Marketing".

---

### Intermediate: Input Messages and Error Alerts

* Input Message:

  * Appears when the cell is selected.
  * Guides the user before data entry.
* Error Alert:

  * Appears after invalid data is entered.
* Alert types:

  * Stop blocks invalid entry.
  * Warning allows entry after confirmation.
  * Information allows entry with a message.

---

### Advanced: Restrictions and Custom Formulas

* Whole Numbers or Decimals:

  * Restrict values like age or price ranges.
* Date and Time:

  * Ensure logical date order, start date before end date.
* Text Length:

  * Limit character count, for example User ID length.
* Custom Formula:

  * Enforce rules like preventing duplicate values.

---

## 2. Real-World Applications

* HR systems:

  * Department selection using drop-down lists.
* Financial models:

  * Restrict years to a fixed range.
* Attendance tracking:

  * Allow only P, A, or L.
* Feedback forms:

  * Restrict ratings between 1 and 5.

---

## 3. Student Task: School Enrollment Form

Objective:

* Create an error-free data entry row.

Validation rules:

* Student Name:

  * Text length limited to 20 characters.
* Grade:

  * Drop-down list with 1st, 2nd, 3rd.
* Admission Date:

  * Date restricted between 01-Jan and 31-Dec.
* Age:

  * Whole number between 5 and 18.
* Roll Number:

  * Custom rule to prevent duplicates.

---

## 4. Interview Practice Questions

* Easy:

  * Create a Gender drop-down list.
* Medium:

  * Difference between Stop and Warning alerts.
* Medium:

  * Restrict dates to future only.
* Hard:

  * Link a drop-down list from another sheet.
* Advanced:

  * Custom formula to enforce minimum 8-character passwords.

