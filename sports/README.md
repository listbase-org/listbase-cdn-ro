# Sport (Sports)

1 datasets — 20 records

> Browse at [listbase.org/ro/sports/](https://listbase.org/ro/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Canale TV de sport din România (Sports TV channels)](ro-canale-tv-sport.json) | 20 | 10 KB | [CSV](ro-canale-tv-sport_RO.csv) | [Excel](ro-canale-tv-sport_RO.xlsx) | [View](https://listbase.org/ro/sports/ro-canale-tv-sport/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/sports/ro-canale-tv-sport.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/sports/)
