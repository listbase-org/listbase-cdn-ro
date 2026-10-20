# Mediu (Environment)

2 datasets — 613 records

> Browse at [listbase.org/ro/environment/](https://listbase.org/ro/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Centrale electrice din România](ro-centrale-electrice.json) | 608 | 308 KB | [CSV](ro-centrale-electrice_RO.csv) | [Excel](ro-centrale-electrice_RO.xlsx) | [View](https://listbase.org/ro/environment/ro-centrale-electrice/) |
| [Centrale nucleare în România](ro-centrale-nucleare.json) | 5 | 5 KB | [CSV](ro-centrale-nucleare_RO.csv) | [Excel](ro-centrale-nucleare_RO.xlsx) | [View](https://listbase.org/ro/environment/ro-centrale-nucleare/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/environment/ro-centrale-electrice.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/environment/)
