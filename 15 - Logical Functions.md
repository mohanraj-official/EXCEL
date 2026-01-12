# Excel Logical Functions – Quick Reference

| Function | Exact Syntax | Purpose (What it does) | Real-World Use Case |
|---------|--------------|------------------------|---------------------|
| IF | =IF(logical_test, value_if_true, value_if_false) | Checks a condition and returns one result if TRUE and another if FALSE. | Mark students as "Pass" or "Fail" based on exam score. |
| IFERROR | =IFERROR(value, value_if_error) | Replaces any error result with a custom output. | Show "0" or "Calculation Pending" instead of #DIV/0!. |
| IFNA | =IFNA(value, value_if_na) | Handles only #N/A errors. | Display "Not Found" when an ID lookup fails. |
| AND | =AND(logical1, [logical2], ...) | Returns TRUE only when all conditions are TRUE. | Check if a candidate meets age and qualification rules. |
| OR | =OR(logical1, [logical2], ...) | Returns TRUE when at least one condition is TRUE. | Check discount eligibility based on membership or spending. |
| NOT | =NOT(logical) | Reverses a logical result. | Identify items that are not discontinued. |


<BR><BR>

[DOWNLOAD THE DATASET](../EXCEL/ASSETS/THE%20GLOBAL%20E-TECH%20COMMERCE_DATE.txt)



### Easy Level

| Question No | Interview Scenario Question |
|------------|-----------------------------|
| 1 | Identify all orders where sales value is zero and label them as "No Sale", others as "Sale Done". |
| 2 | Mark each order as "High Discount" if the discount percentage is more than 10%, otherwise mark it as "Low Discount". |
| 3 | Display "Payment Issue" for orders where payment status shows an error value, otherwise show the original status. |
| 4 | Flag orders as "Out of Stock" when stock level is zero, otherwise show "In Stock". |
| 5 | Replace missing customer feedback with the text "Feedback Not Given". |
| 6 | Identify orders where units sold are zero and return a custom message saying "Order Not Completed". |
| 7 | Show "Return Raised" for orders with return request marked Yes, otherwise show "No Return". |
| 8 | Label customers as "Bulk Buyer" when units are greater than or equal to 5. |
| 9 | Highlight orders where shipping days exceed 7 as "Delayed". |
| 10 | Replace any invalid numeric error in sales or cost columns with zero. |

---

### Medium Level

| Question No | Interview Scenario Question |
|------------|-----------------------------|
| 11 | Classify orders as "Profitable" when sales amount is greater than cost, otherwise mark them as "Loss". |
| 12 | Identify high-priority orders where payment is completed and shipping days are less than or equal to 3. |
| 13 | Mark customers as "Risky" when payment is pending and stock level is zero. |
| 14 | Display "Check Payment" when payment status contains missing or error values. |
| 15 | Categorize orders into "Fast Delivery" or "Slow Delivery" based on a shipping days threshold of 5. |
| 16 | Flag orders eligible for review when customer feedback is negative or missing. |
| 17 | Identify low inventory risk when stock level is below 5 and units sold is greater than zero. |
| 18 | Create a status column that shows "Corporate Priority" only for corporate customers with sales above 3000. |
| 19 | Mark orders as "Discount Misuse" when a discount is applied but sales value is zero. |
| 20 | Show "Return Attention Needed" for orders with return request Yes and negative feedback. |

---

### Hard Level

| Question No | Interview Scenario Question |
|------------|-----------------------------|
| 21 | Create a final order status that shows "Critical Issue" when sales is zero, payment has an error, and stock is zero. |
| 22 | Identify revenue leakage orders where cost is greater than sales and a discount is applied. |
| 23 | Flag operational failure orders where shipping days exceed 10 and customer feedback is missing. |
| 24 | Build a decision column that marks "Immediate Action" when payment is pending, return request is Yes, and feedback is negative. |
| 25 | Generate a performance tag that shows "Top Performer" only when sales exceed 2000, payment is completed, shipping is under 3 days, and no return is requested. |
