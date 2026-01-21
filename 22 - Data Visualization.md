# BEGINNERS CHARTS

| Chart Type      | What it is                | Why use it               | When to use             | Data required                    | Max categories for good view |
| --------------- | ------------------------- | ------------------------ | ----------------------- | -------------------------------- | ---------------------------- |
| Column Chart    | Vertical bars             | Easy height comparison   | Compare few categories  | 1 text column + 1 numeric column | Up to 6–7                    |
| Bar Chart       | Horizontal bars           | Handles long names       | Compare many categories | 1 text column + 1 numeric column | 10–15                        |
| Line Chart      | Points connected by lines | Shows movement over time | Trend analysis          | 1 date column + 1 numeric column | 1–3 lines                    |
| Area Chart      | Line with filled area     | Shows volume over time   | Emphasize magnitude     | 1 date column + 1 numeric column | 1–2                          |
| Pie Chart       | Circle split into slices  | Shows part of total      | Percentage contribution | 1 text column + 1 numeric column | 2–5 only                     |
| Doughnut Chart  | Pie with center hole      | Cleaner composition view | Simple proportions      | 1 text column + 1 numeric column | 2–4                          |
| Treemap         | Nested rectangles         | Shows hierarchy + size   | Many categories         | Category + subcategory + value   | 10–30                        |
| Scatter Plot    | X-Y dots                  | Shows relationship       | Correlation analysis    | 2 numeric columns                | 100s of points               |
| Histogram       | Frequency bars            | Shows distribution       | Score or range analysis | 1 numeric column                 | Auto-binned                  |
| Waterfall Chart | Floating bars             | Explains step changes    | Profit or cash flow     | Category + numeric changes       | 5–10                         |


<br>
<br>

# ADVANCED CHARTS

| Chart Type       | What it is                          | Why use it                 | When to use             | Data required                     | Max categories for clean view |
| ---------------- | ----------------------------------- | -------------------------- | ----------------------- | --------------------------------- | ----------------------------- |
| Box and Whisker  | Shows median, spread, outliers      | Understand distribution    | Compare data spread     | 1 numeric column, optional groups | 3–6 groups                    |
| Pareto Chart     | Sorted columns with cumulative line | Identify top contributors  | 80–20 analysis          | Category + numeric count          | Up to 10                      |
| Sunburst Chart   | Circular hierarchy chart            | Show multi-level structure | Parent–child data       | Multiple category levels + value  | 3–4 levels                    |
| Stock Chart      | OHLC price chart                    | Track financial movement   | Market analysis         | Date + Open, High, Low, Close     | Time-based                    |
| Funnel Chart     | Stage-wise decreasing bars          | Show drop-offs             | Sales or hiring funnel  | Stage + numeric value             | 4–7 stages                    |
| Combo Chart      | Two chart types together            | Compare scales             | Actual vs target        | Category + 2 numeric columns      | 6–10                          |
| Surface Chart    | 3D surface plot                     | Find optimal values        | Scientific analysis     | Numeric matrix                    | Grid-based                    |
| Radar Chart      | Values around a circle              | Compare profiles           | Skill or KPI comparison | Multiple metrics per item         | 5–8 metrics                   |
| Filled Map Chart | Data on geographic map              | Regional comparison        | Location-based analysis | Location + numeric value          | Depends on map                |




<br>
<br>

# SPARKLINE

| Sparkline Type     | What it shows             | Why use it               | When to use               | Data required                    | Best use case              |
| ------------------ | ------------------------- | ------------------------ | ------------------------- | -------------------------------- | -------------------------- |
| Line Sparkline     | Trend as a small line     | Shows direction quickly  | Time-based change per row | Multiple numeric values in a row | Monthly sales per employee |
| Column Sparkline   | Vertical mini bars        | Shows comparison clearly | Discrete values           | Multiple numeric values in a row | Marks per subject          |
| Win/Loss Sparkline | Positive vs negative only | Highlights gain or loss  | Binary performance        | Positive and negative values     | Profit vs loss per month   |



<br>
<br>


[DOWNLOAD THE DATASET](../EXCEL/ASSETS/CHARTS.txt)


| Level        | Chart Category | Specific Chart Task                                                              | Selection Strategy (Columns to Select)        |
| ------------ | -------------- | -------------------------------------------------------------------------------- | --------------------------------------------- |
| Basic        | Comparison     | 1. Clustered Column Chart. Show total Revenue for each of the 4 Regions.         | Region, Revenue                               |
| Basic        | Comparison     | 2. Bar Chart. Show the average CustomerRating for each Product.                  | Product, CustomerRating                       |
| Basic        | Composition    | 3. Pie Chart. Show the proportion of UnitsSold across Categories.                | Category, UnitsSold                           |
| Basic        | Composition    | 4. Doughnut Chart. Show how much Profit each Region contributes.                 | Region, Profit                                |
| Intermediate | Trends         | 5. Line Chart. Plot the daily trend of Revenue from January to April.            | Date, Revenue                                 |
| Intermediate | Trends         | 6. Area Chart. Show cumulative Profit growth over time.                          | Date, Profit                                  |
| Intermediate | Relationship   | 7. Scatter Plot. Analyze the relationship between DiscountPercent and UnitsSold. | DiscountPercent, UnitsSold                    |
| Intermediate | Relationship   | 8. Bubble Chart. Plot Cost versus Revenue with bubble size as UnitsSold.         | Cost, Revenue, UnitsSold                      |
| Intermediate | Distribution   | 9. Histogram. Show frequency distribution of DeliveryDays.                       | DeliveryDays                                  |
| Intermediate | Distribution   | 10. Box and Whisker Plot. Show Revenue distribution across Categories.           | Category, Revenue                             |
| Advanced     | Hierarchy      | 11. Treemap. Visualize Revenue by Category and SubCategory.                      | Category, SubCategory, Revenue                |
| Advanced     | Hierarchy      | 12. Sunburst Chart. Show sales hierarchy from Region to Category.                | Region, Category, Revenue                     |
| Advanced     | Financial      | 13. Waterfall Chart. Start with Revenue, subtract Cost, end at Profit.           | Revenue, Cost, Profit                         |
| Advanced     | Financial      | 14. Stock Chart. Represent Profit using calculated High, Low, Close ranges.      | Date, Profit (calculated range)               |
| Advanced     | Specialized    | 15. Radar Chart. Compare two Products using Rating, DeliveryDays, and Profit.    | Product, CustomerRating, DeliveryDays, Profit |
| Advanced     | Specialized    | 16. Funnel Chart. Show drop-off from UnitsSold to Delivered.                     | Product, UnitsSold, Delivered                 |
| Advanced     | Specialized    | 17. Map Chart. Visualize Revenue intensity by geographic area.                   | Region or Country, Revenue                    |
| Expert       | Dynamic        | 18. Combo Chart. Revenue as Columns, ProfitPercent as Line on secondary axis.    | Product, Revenue, ProfitPercent               |
| Expert       | Dynamic        | 19. Sparklines. Create per-row mini trends using numeric metrics.                | Revenue, Cost, Profit                         |
| Expert       | Dynamic        | 20. Pivot Chart. Interactive chart with Category slicer.                         | Entire Dataset                                |


