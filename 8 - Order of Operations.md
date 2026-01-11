# Module 8 – Order of Operations

This module explains how Excel decides the sequence of calculations inside a formula. Misunderstanding this rule leads to incorrect results even when the formula looks correct.

---

## What Is Order of Operations

- Order of operations defines the sequence Excel follows to calculate a formula.
- Excel does not calculate from left to right.
- It follows a fixed priority rule.

---

## BODMAS / PEDMAS Rule

Excel uses the same mathematical rule.

Order followed by Excel:

1. Parentheses  
2. Exponents  
3. Multiplication and Division  
4. Addition and Subtraction  

If two operators have the same priority, Excel calculates from left to right.

---

## Why Order of Operations Matters

- Incorrect formulas return wrong values.
- Financial, tax, and pricing calculations depend on accuracy.
- Small errors multiply across large datasets.

Example:

- =10 + 5 * 2  
  Result: 20  

- =(10 + 5) * 2  
  Result: 30  

Same numbers. Different results.

---

## When Order of Operations Becomes Critical

- Tax and discount calculations
- Salary and incentive formulas
- Business forecasts
- Data models with multiple conditions

---

## How Excel Evaluates a Formula

- Excel evaluates one operator at a time.
- Parentheses override default order.
- You can check evaluation step by step using:
  - Formula tab
  - Evaluate Formula option

---

## Practice Dataset 1: Invoice Calculation

| Row | Item | Quantity | Unit Price | Discount % | Tax % |
|----|------|----------|-----------|------------|-------|
| 2 | Pen | 10 | 20 | 5% | 18% |
| 3 | Book | 5 | 150 | 10% | 18% |
| 4 | Bag | 2 | 900 | 8% | 18% |

### Practice Questions

1. Calculate the base amount using Quantity and Unit Price.
2. Calculate discount value from the base amount.
3. Calculate final amount after discount and tax.
4. Use parentheses so discount applies before tax.

---

## Practice Dataset 2: Salary Sheet

| Row | Employee | Basic Salary | HRA % | Bonus |
|----|---------|--------------|------|------|
| 2 | Arun | 25,000 | 20% | 3,000 |
| 3 | Meena | 32,000 | 25% | 4,000 |
| 4 | Ravi | 28,000 | 22% | 3,500 |

### Practice Questions

5. Calculate HRA amount from Basic Salary.
6. Calculate Gross Salary including HRA and Bonus.
7. Test the result with and without parentheses.

---

## Practice Dataset 3: Monthly Expense Analysis

| Row | Category | Expense | Increase % | Months |
|----|----------|---------|-----------|--------|
| 2 | Rent | 12,000 | 5% | 12 |
| 3 | Food | 6,500 | 8% | 12 |
| 4 | Travel | 3,200 | 10% | 12 |

### Practice Questions

8. Calculate increased monthly expense.
9. Calculate annual expense after increase.
10. Verify results using different bracket placements.

---

## Practice Dataset 4: Sales Commission

| Row | Salesperson | Sales Amount | Commission % | Bonus |
|----|------------|--------------|--------------|-------|
| 2 | Asha | 150,000 | 5% | 2,000 |
| 3 | Kiran | 220,000 | 6% | 3,000 |
| 4 | Nikhil | 180,000 | 5.5% | 2,500 |

### Practice Questions

11. Calculate commission value.
12. Calculate total payout including bonus.
13. Check impact of incorrect operator order.

---

## Formula Evaluation Practice

14. Use Evaluate Formula to:
- Track each calculation step.
- Identify where Excel applies multiplication, division, and addition.
- Compare results with manual calculation.

---

## Key Learning Outcome

- Excel follows strict calculation rules.
- Parentheses control logic.
- Evaluation tools help debug formulas.
- Correct order ensures reliable business results.


