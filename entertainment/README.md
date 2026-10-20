# Divertisment (Entertainment)

10 datasets — 602 records

> Browse at [listbase.org/ro/entertainment/](https://listbase.org/ro/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Fluxuri de emisie ale canalelor TV din România (Romanian TV channel feeds)](ro-canale-tv-fluxuri.json) | 262 | 73 KB | [CSV](ro-canale-tv-fluxuri_RO.csv) | [Excel](ro-canale-tv-fluxuri_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-fluxuri/) |
| [Canale de televiziune din România](ro-canale-tv.json) | 208 | 76 KB | [CSV](ro-canale-tv_RO.csv) | [Excel](ro-canale-tv_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv/) |
| [Canale TV generaliste din România (General TV channels)](ro-canale-tv-generaliste.json) | 50 | 20 KB | [CSV](ro-canale-tv-generaliste_RO.csv) | [Excel](ro-canale-tv-generaliste_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-generaliste/) |
| [Canale TV de muzică din România (Music TV channels)](ro-canale-tv-muzica.json) | 25 | 11 KB | [CSV](ro-canale-tv-muzica_RO.csv) | [Excel](ro-canale-tv-muzica_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-muzica/) |
| [Canale TV de știri din România (News TV channels)](ro-canale-tv-stiri.json) | 16 | 8 KB | [CSV](ro-canale-tv-stiri_RO.csv) | [Excel](ro-canale-tv-stiri_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-stiri/) |
| [Canale TV de filme din România (Movies TV channels)](ro-canale-tv-filme.json) | 12 | 7 KB | [CSV](ro-canale-tv-filme_RO.csv) | [Excel](ro-canale-tv-filme_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-filme/) |
| [Canale TV de divertisment din România (Entertainment TV channels)](ro-canale-tv-divertisment.json) | 9 | 6 KB | [CSV](ro-canale-tv-divertisment_RO.csv) | [Excel](ro-canale-tv-divertisment_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-divertisment/) |
| [Canale TV pentru copii din România (Kids TV channels)](ro-canale-tv-copii.json) | 8 | 5 KB | [CSV](ro-canale-tv-copii_RO.csv) | [Excel](ro-canale-tv-copii_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-copii/) |
| [Canale TV de lifestyle din România (Lifestyle TV channels)](ro-canale-tv-lifestyle.json) | 6 | 5 KB | [CSV](ro-canale-tv-lifestyle_RO.csv) | [Excel](ro-canale-tv-lifestyle_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-lifestyle/) |
| [Canale TV religioase din România (Religious TV channels)](ro-canale-tv-religie.json) | 6 | 5 KB | [CSV](ro-canale-tv-religie_RO.csv) | [Excel](ro-canale-tv-religie_RO.xlsx) | [View](https://listbase.org/ro/entertainment/ro-canale-tv-religie/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/entertainment/ro-canale-tv-fluxuri.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/entertainment/)
