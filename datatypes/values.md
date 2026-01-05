---
title: Values
---

# Values

A **value** is a single data entry inside a datatype.

Values are what DataTyper uses to fill your designs.

---

## One value per line

Each line inside a datatype input field is treated as a separate value.

Important rules:

- One line equals one value
- Empty lines are ignored
- Commas are treated as regular characters

Example:

John Smith
Jane Doe
Alex Johnson

This creates three separate values.

---

## How values are used

When filling designs:

- Values are applied to selected layers in order
- If there are more layers than values, values are reused cyclically
- Sorting and randomization affect the order of values

Understanding how values work is essential for predictable filling results.

---
<!-- DATATYPER_DOCS_NAV -->
← Previous: [Overview](/datatypes/overview)  
Next: [Editing](/datatypes/editing) →
