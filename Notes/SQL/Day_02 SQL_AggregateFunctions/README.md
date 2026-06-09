
# Day 2 - SQL Aggregate Functions

## COUNT()

Returns the total number of rows.

### Example

SELECT COUNT(*)
FROM Employees;

---

## SUM()

Returns the sum of values.

### Example

SELECT SUM(Salary)
FROM Employees;

---

## AVG()

Returns the average value.

### Example

SELECT AVG(Salary)
FROM Employees;

---

## MIN()

Returns the minimum value.

### Example

SELECT MIN(Salary)
FROM Employees;

---

## MAX()

Returns the maximum value.

### Example

SELECT MAX(Salary)
FROM Employees;

---

## GROUP BY

Groups rows with similar values.

### Example

SELECT Department,
COUNT(*)
FROM Employees
GROUP BY Department;

---

## HAVING

Filters grouped records.

### Example

SELECT Department,
AVG(Salary)
FROM Employees
GROUP BY Department
HAVING AVG(Salary) > 50000;

---

## Key Takeaways

- Aggregate functions summarize data.
- GROUP BY creates categories.
- HAVING filters grouped results.
