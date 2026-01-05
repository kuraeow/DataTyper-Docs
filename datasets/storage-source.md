---
title: Storage Source
---

# Storage Source

Each dataset in DataTyper uses a **storage source** that defines where its data is stored and synchronized.

## On this page

- [DataTyper Cloud](#datatyper-cloud)
- [Google Sheets as a storage source](#google-sheets-as-a-storage-source)
- [Choosing the right storage source](#choosing-the-right-storage-source)


You can change the storage source at any time.

---

## DataTyper Cloud

**DataTyper Cloud** is the default storage source.

Features:
- Cloud-based storage
- Real-time collaboration
- Read and write access
- Automatic synchronization between users

This option works out of the box and requires no additional configuration.

---

## Google Sheets as a storage source

You can use **Google Sheets** as an alternative storage source for a dataset.

This allows you to manage your data directly in a spreadsheet while still using it inside DataTyper.

---

### Connecting a Google Sheet

To connect a dataset to Google Sheets:

1. Select Google Sheets as the storage source
2. Paste the Google Sheet URL
3. Save the dataset settings

---

### Read-only mode

By default, Google Sheets are connected in **read-only mode**.

In this mode:
- Data is read from the spreadsheet
- Changes made in Google Sheets appear in DataTyper
- Editing data inside the plugin is disabled

---

### Two-way synchronization

After authorizing with Google, DataTyper enables **two-way synchronization**.

With two-way sync:
- Changes made in DataTyper update the Google Sheet
- Changes made in the Google Sheet update DataTyper
- Both systems stay in sync automatically

---

## Choosing the right storage source

Use DataTyper Cloud if you:
- want full editing inside the plugin
- rely on collaboration features

Use Google Sheets if you:
- prefer managing data in spreadsheets
- need external visibility or automation

<!-- DATATYPER_DOCS_NAV -->
<div class="docs-page-nav">
  <a href="/datasets/delete">← Delete</a>
  <a href="/datasets/import-export">Import / Export CSV →</a>
</div>
