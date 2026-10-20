# Alimentație (Food & Nutrition)

2 datasets — 8,521 records

> Browse at [listbase.org/ro/food/](https://listbase.org/ro/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restaurante din România](ro-restaurante.json) | 6,137 | 1409 KB | [CSV](ro-restaurante_RO.csv) | [Excel](ro-restaurante_RO.xlsx) | [View](https://listbase.org/ro/food/ro-restaurante/) |
| [Unități fast-food din România](ro-fast-food.json) | 2,384 | 538 KB | [CSV](ro-fast-food_RO.csv) | [Excel](ro-fast-food_RO.xlsx) | [View](https://listbase.org/ro/food/ro-fast-food/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/food/ro-restaurante.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/food/)
