# Turism (Tourism)

2 datasets — 3,640 records

> Browse at [listbase.org/ro/tourism/](https://listbase.org/ro/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Hoteluri din România](ro-hoteluri.json) | 2,934 | 646 KB | [CSV](ro-hoteluri_RO.csv) | [Excel](ro-hoteluri_RO.xlsx) | [View](https://listbase.org/ro/tourism/ro-hoteluri/) |
| [Atracții turistice din România](ro-atractii-turistice.json) | 706 | 168 KB | [CSV](ro-atractii-turistice_RO.csv) | [Excel](ro-atractii-turistice_RO.xlsx) | [View](https://listbase.org/ro/tourism/ro-atractii-turistice/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/tourism/ro-hoteluri.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/tourism/)
