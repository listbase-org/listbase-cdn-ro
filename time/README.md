# Timp și calendar (Time & Calendar)

2 datasets — 584 records

> Browse at [listbase.org/ro/time/](https://listbase.org/ro/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sărbători legale în România (1997–2030) — multilingual completos](ro-sarbatori-completos.json) | 408 | 127 KB | [CSV](ro-sarbatori-completos_RO.csv) | [Excel](ro-sarbatori-completos_RO.xlsx) | [View](https://listbase.org/ro/time/ro-sarbatori-completos/) |
| [Sărbători legale din România (multilingv, 2020–2030)](ro-sarbatori-multilingva.json) | 176 | 81 KB | [CSV](ro-sarbatori-multilingva_RO.csv) | [Excel](ro-sarbatori-multilingva_RO.xlsx) | [View](https://listbase.org/ro/time/ro-sarbatori-multilingva/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/time/ro-sarbatori-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/time/)
