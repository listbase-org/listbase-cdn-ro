# Cultură și religie (Culture & Religion)

3 datasets — 1,200 records

> Browse at [listbase.org/ro/culture/](https://listbase.org/ro/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Muzee din România (Museums in Romania)](ro-muzee.json) | 937 | 245 KB | [CSV](ro-muzee_RO.csv) | [Excel](ro-muzee_RO.xlsx) | [View](https://listbase.org/ro/culture/ro-muzee/) |
| [Mănăstiri din România](ro-manastiri.json) | 255 | 64 KB | [CSV](ro-manastiri_RO.csv) | [Excel](ro-manastiri_RO.xlsx) | [View](https://listbase.org/ro/culture/ro-manastiri/) |
| [Patrimoniul mondial UNESCO în România](ro-patrimoniul-mondial-unesco.json) | 8 | 9 KB | [CSV](ro-patrimoniul-mondial-unesco_RO.csv) | [Excel](ro-patrimoniul-mondial-unesco_RO.xlsx) | [View](https://listbase.org/ro/culture/ro-patrimoniul-mondial-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/culture/ro-muzee.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/culture/)
