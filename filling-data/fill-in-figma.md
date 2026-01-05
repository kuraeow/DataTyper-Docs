---
title: Fill in Figma
---

# Fill Selected

Fill Selected applies values from selected datatypes to the currently selected text layers in Figma.

## On this page

- [How Fill Selected works](#how-fill-selected-works)
- [Cyclic value assignment](#cyclic-value-assignment)
- [How multi-datatype fill works](#how-multi-datatype-fill-works)
- [Typical use cases](#typical-use-cases)
- [Available sorting options](#available-sorting-options)
- [When to use sorting](#when-to-use-sorting)
- [How randomization works](#how-randomization-works)
- [When to use randomization](#when-to-use-randomization)


---

## How Fill Selected works

1. Select one or more text layers in Figma
2. Select one or more datatypes in DataTyper
3. Click **Fill selected**

DataTyper assigns values to layers in order.

---

## Cyclic value assignment

If there are more layers than values:

- Values are reused cyclically
- Filling continues until all selected layers are filled

This ensures that filling always completes, even with limited data.

---

# Multi-Datatype Fill

Multi-datatype fill allows you to use values from multiple datatypes in a single fill operation.

---

## How multi-datatype fill works

1. Select multiple datatypes using checkboxes
2. Select text layers in Figma
3. Click **Fill selected**

Values from all selected datatypes are combined into a single sequence.

---

## Typical use cases

Multi-datatype fill is useful when:

- Filling mixed content layouts
- Combining names, titles, and descriptions
- Creating varied mock content quickly

The combined values follow the same sorting and randomization rules as single-datatype fills.

---

# Sorting

Sorting controls the order in which values are applied during filling.

---

## Available sorting options

DataTyper provides the following sorting modes:

- Default — original order of values
- Min to Max — ascending order
- Max to Min — descending order

Sorting affects only the filling order and does not modify stored values.

---

## When to use sorting

Sorting is useful when:

- Filling ordered lists
- Applying numeric or alphabetical sequences
- Ensuring predictable content placement

---

# Randomize

Randomize applies values in a random order when filling designs.

---

## How randomization works

When randomization is enabled:

- Values are shuffled before filling
- Each fill operation produces a different order

Stored values remain unchanged.

---

## When to use randomization

Randomization is useful for:

- Generating realistic mock data
- Avoiding repetitive patterns
- Creating variation in layouts

---
<!-- DATATYPER_DOCS_NAV -->
<div class="docs-page-nav">
  <a href="/filling-data/overview">← Overview</a>
  <a href="/privacy">Privacy Policy →</a>
</div>
