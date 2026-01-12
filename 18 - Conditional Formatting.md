# Module 18 – Conditional Formatting

## Overview

| Aspect         | Details                                    |
| -------------- | ------------------------------------------ |
| Topic          | Conditional Formatting                     |
| Purpose        | Change cell appearance based on conditions |
| Used For       | Highlight trends, exceptions, and patterns |
| Formula Needed | No, in most cases                          |
| Output         | Better readability and faster analysis     |

---

## Highlighting Cells Based on Rules

| Rule Type        | What It Does                        | When You Use It         | Example                |
| ---------------- | ----------------------------------- | ----------------------- | ---------------------- |
| Greater Than     | Highlights values above a limit     | High scores, high sales | Sales > 50000          |
| Less Than        | Highlights values below a limit     | Fail marks, low stock   | Marks < 35             |
| Between          | Highlights values in a range        | Performance bands       | Attendance 75–90       |
| Equal To         | Highlights exact matches            | Category checks         | City = Chennai         |
| Text Contains    | Highlights cells with specific text | Name or status check    | Status contains "Late" |
| Date Occurring   | Highlights dates                    | Deadlines, due dates    | Due this week          |
| Duplicate Values | Finds repeated data                 | Data validation         | Duplicate Student_ID   |

<BR>

# Conditional Formatting – Types

## Highlight Cells Rules

* Greater Than
* Less Than
* Between
* Equal To
* Text That Contains
* A Date Occurring
* Duplicate Values

## Top/Bottom Rules

* Top 10 Items
* Top 10 Percent
* Bottom 10 Items
* Bottom 10 Percent
* Above Average
* Below Average

## Data Bars

* Solid Fill
* Gradient Fill

## Color Scales

* 2-Color Scale
* 3-Color Scale

## Icon Sets

* Directional Arrows
* Shapes
* Indicators
* Ratings

## Clear Rules

* Clear Rules from Selected Cells
* Clear Rules from Entire Sheet





<BR>
<BR>

[DOWNLOAD THE DATASET](../EXCEL/ASSETS/CONDITIONAL%20FORMATTING.txt)



Below is a clean, student-friendly Markdown file.
Same intent. Same logic.
Questions are summarized.
Each question clearly states what to format and how.
Each level has its own table.

---

# Module – Conditional Formatting Practice (School Dataset)

## Level 1 – Basic Cell Highlighting

| Q.No | Scenario                   | Column / Range    | Rule Type                     | Format to Apply          |
| ---- | -------------------------- | ----------------- | ----------------------------- | ------------------------ |
| 1    | Low attendance below 75    | Attendance_%      | Less Than 75                  | Red Fill                 |
| 2    | Final score above 95       | Final_Score       | Greater Than 95               | Green Fill               |
| 3    | Assignment not submitted   | Assignment_Status | Text Contains "Not Submitted" | Yellow Fill              |
| 4    | Borderline midterm scores  | Midterm_Score     | Between 40 and 50             | Light Orange Fill        |
| 5    | Duplicate student names    | Student_Name      | Duplicate Values              | Default Duplicate Format |
| 6    | Top 10 percent students    | Total_Avg         | Top 10%                       | Highlighted Fill         |
| 7    | Scores above class average | Final_Score       | Above Average                 | Light Green Fill         |
| 8    | Specific student search    | Student_Name      | Equal To "Aarav Sharma"       | Highlight Fill           |

---

## Level 2 – Visual Analytics (Built-in Visual Tools)

| Q.No | Scenario                  | Column / Range    | Tool Used       | Format to Apply            |
| ---- | ------------------------- | ----------------- | --------------- | -------------------------- |
| 9    | Class performance heatmap | Total_Avg         | Color Scale     | 3-Color (Red-Yellow-Green) |
| 10   | Score strength comparison | Midterm_Score     | Data Bars       | Blue Data Bars             |
| 11   | Performance tiers         | Final_Score       | Icon Sets       | 4-Arrow Icons              |
| 12   | Attendance progress bar   | Attendance_%      | Data Bars       | Solid Green, Max 100       |
| 13   | Pass or fail indicator    | Total_Avg         | Icon Sets       | Traffic Lights             |
| 14   | Bottom performers         | Final_Score       | Bottom 10 Items | Orange Fill                |
| 15   | Assignment status flags   | Assignment_Status | Icon Sets       | 3 Flags (numeric mapping)  |

---

## Level 3 – Advanced Formula-Based Row Formatting

| Q.No | Scenario                 | Condition Logic                     | Format Scope | Format to Apply     |
| ---- | ------------------------ | ----------------------------------- | ------------ | ------------------- |
| 16   | Assignment not submitted | Assignment_Status = "Not Submitted" | Entire Row   | Light Grey Fill     |
| 17   | Critical risk student    | Attendance < 60 AND Final < 40      | Entire Row   | Bright Red Fill     |
| 18   | Honor roll student       | Total_Avg > 90                      | Entire Row   | Gold / Light Yellow |
| 19   | Zebra striping           | ISODD(ROW())                        | Entire Row   | Light Blue Fill     |
| 20   | Search highlight         | Name matches value in J1            | Entire Row   | Highlight Fill      |
| 21   | High effort, low result  | Attendance high AND Avg low         | Entire Row   | Purple Fill         |
| 22   | Pending assignment       | Assignment_Status = "Pending"       | Entire Row   | Orange Fill         |
| 23   | Top scorer               | Final_Score = MAX(Final_Score)      | Entire Row   | Highlight Fill      |
| 24   | Strong pass condition    | Midterm > 70 AND Final > 70         | Entire Row   | Green Fill          |
| 25   | Data audit               | Any blank cell in row               | Entire Row   | Red Border or Fill  |

---

## Important Student Note

When formatting **entire rows**, lock the column using `$`.
Example:
=$C2<75

This prevents formatting from shifting across columns.
