
# Day 2 - Excel Functions

## VLOOKUP

VLOOKUP searches for a value in the first column of a table and returns a corresponding value.

### Syntax

=VLOOKUP(lookup_value, table_array, col_index_num, FALSE)

### Example

=VLOOKUP(101,A2:C10,3,FALSE)

---

## XLOOKUP

XLOOKUP is a modern replacement for VLOOKUP.

### Syntax

=XLOOKUP(lookup_value, lookup_array, return_array)

### Example

=XLOOKUP(101,A2:A10,C2:C10)

---

## Conditional Formatting

Conditional Formatting changes cell appearance based on conditions.

### Uses

- Highlight top performers
- Identify low values
- Detect duplicates

---

## Data Validation

Data Validation restricts invalid inputs.

### Example

Allow only numbers between 1 and 100.

---

## Key Takeaways

- VLOOKUP retrieves data vertically.
- XLOOKUP is more flexible.
- Conditional Formatting improves visibility.
- Data Validation improves data quality.
