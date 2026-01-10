# Module 7 – Cell References

Cell references define how Excel formulas behave when copied. Understanding relative and absolute references is essential for accurate calculations and scalable models.

---

## What Is a Cell Reference

- A cell reference points to a cell used in a formula.
- Example:
  - =A1 + B1
- Excel recalculates results based on referenced cells.

---

## Types of Cell References

Excel uses two primary reference types in daily work.

---

## 1. Relative Cell Reference

### Definition
- A relative reference changes when a formula is copied.
- Default reference type in Excel.

### Example
- Formula in C2:
  - =A2 * B2
- Copy the formula to C3.
- Excel updates it to:
  - =A3 * B3

### Real-World Use Case
- Monthly expense calculation.
- Each row represents a transaction.
- Amount is calculated row by row.
- Relative references save time and avoid manual edits.

### When to Use
- Row-wise calculations.
- Column-wise totals.
- Repeating formulas across datasets.

---

## 2. Absolute Cell Reference

### Definition
- An absolute reference remains fixed when copied.
- Uses the dollar symbol.

### Format
- $A$1

### Shortcut
- Press F4 after selecting a cell reference.
- Toggles through:
  - A1
  - $A$1
  - A$1
  - $A1

---

## Absolute Reference Example

### Scenario
- Tax rate stored in one cell.

### Setup
- Cell B1: Tax Rate = 18%
- Cell C2 formula:
  - =A2 * $B$1

### Copy Behavior
- Copy the formula down.
- A2 changes to A3, A4, A5.
- B1 remains fixed.

### Result
- Correct tax calculation for all rows.

---

## Real-World Use Cases for Absolute References

- Tax rate calculations.
- Discount percentage.
- Currency conversion rate.
- Fixed commission rates.
- Constant assumptions in financial models.

---

## Relative vs Absolute Reference Comparison

| Aspect | Relative | Absolute |
|-----|--------|---------|
| Changes when copied | Yes | No |
| Default behavior | Yes | No |
| Uses dollar symbol | No | Yes |
| Best for | Repeating data | Fixed values |

---

## Mixed Cell References

### Definition
- Locks either row or column.
- Used when one dimension stays constant.

### Examples
- $A1 locks column A.
- A$1 locks row 1.

### Real-World Use Case
- Price table with fixed product list and changing months.
- Apply formula across rows and columns without breaking logic.

---

## Key Takeaways

- Relative references move with the formula.
- Absolute references stay fixed.
- F4 controls reference locking.
- Correct reference choice prevents calculation errors.






# PRACTICE QUESTIONS

Use the sample tables below. Write formulas and copy them where required. Do not hard-code values.

---

## Table 1: Monthly Sales Data

| Row | Product | Quantity | Unit Price | Total Amount |
|----|--------|----------|-----------|--------------|
| 2 | Pen | 10 | 15 | |
| 3 | Notebook | 5 | 60 | |
| 4 | Marker | 8 | 25 | |
| 5 | Eraser | 20 | 5 | |

### Questions

1. In the Total Amount column, calculate the total for each product using Quantity and Unit Price.  
2. Copy the formula down for all rows without modifying it manually.

---

## Table 2: Tax Configuration

| Cell | Value |
|----|------|
| B1 | 18% |

| Row | Invoice Amount | Tax Amount |
|----|---------------|-----------|
| 2 | 1,200 | |
| 3 | 2,500 | |
| 4 | 3,750 | |
| 5 | 4,100 | |

### Questions

3. Calculate the Tax Amount for each invoice using the tax value provided.  
4. Copy the formula down so it works correctly for all rows.

---

## Table 3: Regional Pricing Matrix

|   | B | C | D | E |
|---|---|---|---|---|
| 1 | Region A | Region B | Region C | Region D |
| 2 | 5% | 8% | 10% | 12% |
| 3 | 1,000 | | | |
| 4 | 2,000 | | | |
| 5 | 3,000 | | | |

### Questions

5. Calculate the value for all empty cells by applying the percentage in Row 2 to the base amount in Column A.  
6. Write one formula and apply it across the entire table.

---

## Table 4: Employee Incentive Sheet

| Row | Employee | Sales Amount | Incentive |
|----|---------|--------------|-----------|
| 2 | Arjun | 50,000 | |
| 3 | Meena | 65,000 | |
| 4 | Ravi | 40,000 | |
| 5 | Sita | 75,000 | |

| Cell | Incentive Rate |
|----|----------------|
| F1 | 6% |

### Questions

7. Calculate the Incentive for each employee using the given rate.  
8. Copy the formula without breaking the calculation.

---

## Table 5: Multiplication Grid

|   | B | C | D | E |
|---|---|---|---|---|
| 1 | 1 | 2 | 3 | 4 |
| 2 | 5 | | | |
| 3 | 6 | | | |
| 4 | 7 | | | |
| 5 | 8 | | | |

### Questions

9. Complete the grid by multiplying row values with column values.  
10. Use a single formula and fill the entire grid.

---

## Table 6: Monthly Expense Forecast

| Row | Month | Expense | Forecast |
|----|------|---------|----------|
| 2 | Jan | 12,000 | |
| 3 | Feb | 14,500 | |
| 4 | Mar | 13,800 | |
| 5 | Apr | 15,200 | |

| Cell | Inflation Rate |
|----|----------------|
| E1 | 4% |

### Questions

11. Calculate the forecasted expense using the given rate.  
12. Apply the formula to all rows correctly.

---

End of practice questions

