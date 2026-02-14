---
title: How to Add a Subcategory
sidebar_position: 2
---

# How to Add a Subcategory

Subcategories are created by adding a subdirectory with a `_category_.json` file.

## Steps

1. Create a directory inside your category (e.g., `docs/top-category-3/my-sub/`)
2. Add a `_category_.json` file:

```json
{
  "label": "My Subcategory",
  "position": 5
}
```

3. Add markdown files inside the subdirectory
4. The subcategory appears as a collapsible group in the sidebar
