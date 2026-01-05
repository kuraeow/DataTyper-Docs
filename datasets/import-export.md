---
title: Import and Export CSV
---

# Import and Export CSV

DataTyper supports importing and exporting datasets using CSV files.

## On this page

- [CSV format](#csv-format)
- [Import rules](#import-behavior)
- [How mapping works](#mapping-and-merge-logic)
- [Preparing your CSV](#preparing-csv-files-correctly)
- [Export](#exporting-to-csv)


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

Here is a simple example you can copy and adjust:

| datatype_name | datatype_value |
|---|---|
| Names | John Smith |
| Names | Jane Doe |
| Emails | john@example.com |
| Emails | jane@example.com |

This creates:

- One datatype named `Names` with two values
- One datatype named `Emails` with two values

##
---
<!-- DATATYPER_DOCS_NAV -->
<div class="docs-page-nav">
  <a href="/datasets/storage-source">← Storage Source</a>
  <a href="/collaboration/overview">Overview →</a>
</div>
