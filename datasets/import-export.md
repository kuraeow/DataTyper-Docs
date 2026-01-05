---
title: Import and Export CSV
---

# Import and Export CSV

DataTyper supports importing and exporting datasets using CSV files.

This makes it easy to migrate data, create backups, or prepare content outside the plugin before using it in Figma.

---

## CSV format

DataTyper expects CSV files with exactly two columns:

datatype_name,datatype_value

- datatype_name — the name of the datatype
- datatype_value — a single value for that datatype

Each row represents one value.

---

## Example CSV

datatype_name,datatype_value
Names,John Smith
Names,Jane Doe
Emails,john@example.com
Emails,jane@example.com

This creates:

- One datatype named Names with two values
- One datatype named Emails with two values

---

## Import behavior

When importing a CSV file, DataTyper follows these rules:

- If a datatype with the same name already exists:
  - Values are added to that datatype
- If the datatype does not exist:
  - A new datatype is created
- Empty rows are ignored
- Invalid rows are skipped

This allows CSV imports to merge with existing data instead of overwriting everything.

---

## Import destination

- If a dataset is active, the data is imported into that dataset
- If no datasets exist, DataTyper creates a new dataset automatically

This ensures you can start using DataTyper directly from a CSV file.

---

## Exporting to CSV

When exporting a dataset:

- All datatypes and values are included
- The exported file uses the same two-column format
- The file name is based on the dataset name

Exporting is useful for:

- backups
- bulk editing
- transferring data between projects

---

## Preparing CSV files correctly

To ensure a successful import:

- Use exact datatype names
- Use one value per row
- Do not combine multiple values in a single cell
- Do not rely on commas as separators inside a value
- Avoid storing sensitive or confidential data

Following these rules guarantees predictable and consistent import results.

---
<!-- DATATYPER_DOCS_NAV -->
← Previous: [Storage Source](/datasets/storage-source)  
Next: [Overview](/collaboration/overview) →
