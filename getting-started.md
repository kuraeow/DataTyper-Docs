---
title: Getting Started
permalink: /
---

# Getting Started

This guide will help you get from opening DataTyper for the first time to filling your Figma designs with real data.

---

## What is DataTyper?

DataTyper is a Figma plugin that lets you manage structured data and use it to fill your designs in seconds.

Instead of manually copying and pasting content, you work with reusable datasets and apply them directly to your design layers.

At a high level, DataTyper works like this:

**Dataset → Datatypes → Values → Fill designs**

---

## Sign in with Figma

<div class="callout note">
<strong>Note</strong><br>
DataTyper uses Figma OAuth. You never create a separate DataTyper password.
</div>

When you open DataTyper for the first time, you’ll be asked to sign in.

DataTyper uses **Figma OAuth** for authentication.

- No passwords are created or stored
- No secret credentials are handled by DataTyper
- Authorization is performed directly by Figma

Once you complete the sign-in flow, DataTyper is ready to use.

- [More about Authentication →](/authentication)

---

## Create your first Dataset

A **Dataset** is a container for your data.  
You can create as many datasets as you need — for different projects, clients, or design systems.

To create your first dataset:

1. Open the DataTyper plugin
2. Click **Create dataset**
3. Enter a name for your dataset

Your dataset becomes the active dataset immediately.

- [More about Datasets →](/datasets/overview)

---

## Add a Datatype

Inside a dataset, data is organized into **Datatypes**.

A **Datatype** represents one category of data, for example:
- Names
- Emails
- Phone numbers
- Titles
- Dates

To add a datatype:

1. Click **Add type**
2. Enter a datatype name
3. Enter values — **one value per line**
4. Save the datatype

- [More about Datatypes →](/datatypes/overview)

---

## What is a Value?

A **Value** is a single data entry inside a datatype.

Important rules:
- **One line equals one value**
- Commas are treated as regular characters
- Empty lines are ignored

Example:<br>
John Smith<br>
Jane Doe<br>
Alex Johnson

This creates **three separate values**, not one combined value.

- [More about Values →](/datatypes/values)

---

## Fill your design

Once you have datatypes with values, you can start filling your designs.

### Fill selected layers

1. Select one or more **text layers** in Figma
2. In DataTyper, select one or more datatypes
3. Click **Fill selected**

DataTyper applies values to the selected layers in order.

If there are more layers than values, values are reused cyclically.

- [More about Filling →](/filling-data/overview)

---

## What’s next?

Now that you understand the basics, you can explore more advanced features:

- Managing multiple datasets
- Importing and exporting data with CSV
- Filling designs with random or sorted data
- Using multiple datatypes at once
- Collaborating with your team
- Connecting datasets to external storage sources

Continue with the next section to learn more about datasets and how they work.

<!-- DATATYPER_DOCS_NAV -->
<div class="docs-page-nav">
  <span></span>
  <a href="/authentication">Authentication →</a>
</div>
