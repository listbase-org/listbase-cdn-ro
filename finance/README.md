# Finanțe și comerț (Finance & Trade)

15 datasets — 869 records

> Browse at [listbase.org/ro/finance/](https://listbase.org/ro/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Piețe din România](ro-piete.json) | 679 | 161 KB | [CSV](ro-piete_RO.csv) | [Excel](ro-piete_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-piete/) |
| [Bănci în Bucharest — coduri SWIFT/BIC](ro-bucharest-banci.json) | 120 | 20 KB | [CSV](ro-bucharest-banci_RO.csv) | [Excel](ro-bucharest-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-bucharest-banci/) |
| [Bănci în Cluj-Napoca — coduri SWIFT/BIC](ro-cluj-napoca-banci.json) | 17 | 5 KB | [CSV](ro-cluj-napoca-banci_RO.csv) | [Excel](ro-cluj-napoca-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-cluj-napoca-banci/) |
| [Bănci în Oradea — coduri SWIFT/BIC](ro-oradea-banci.json) | 7 | 3 KB | [CSV](ro-oradea-banci_RO.csv) | [Excel](ro-oradea-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-oradea-banci/) |
| [Bănci în Arad — coduri SWIFT/BIC](ro-arad-banci.json) | 6 | 3 KB | [CSV](ro-arad-banci_RO.csv) | [Excel](ro-arad-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-arad-banci/) |
| [Bănci în Sibiu — coduri SWIFT/BIC](ro-sibiu-banci.json) | 6 | 3 KB | [CSV](ro-sibiu-banci_RO.csv) | [Excel](ro-sibiu-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-sibiu-banci/) |
| [Bănci în Brasov — coduri SWIFT/BIC](ro-brasov-banci.json) | 5 | 3 KB | [CSV](ro-brasov-banci_RO.csv) | [Excel](ro-brasov-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-brasov-banci/) |
| [Bănci în Targu Mures — coduri SWIFT/BIC](ro-targu-mures-banci.json) | 5 | 3 KB | [CSV](ro-targu-mures-banci_RO.csv) | [Excel](ro-targu-mures-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-targu-mures-banci/) |
| [Bănci în Craiova — coduri SWIFT/BIC](ro-craiova-banci.json) | 4 | 3 KB | [CSV](ro-craiova-banci_RO.csv) | [Excel](ro-craiova-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-craiova-banci/) |
| [Bănci în Galati — coduri SWIFT/BIC](ro-galati-banci.json) | 4 | 3 KB | [CSV](ro-galati-banci_RO.csv) | [Excel](ro-galati-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-galati-banci/) |
| [Bănci în Iasi — coduri SWIFT/BIC](ro-iasi-banci.json) | 4 | 3 KB | [CSV](ro-iasi-banci_RO.csv) | [Excel](ro-iasi-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-iasi-banci/) |
| [Bănci în Constanta — coduri SWIFT/BIC](ro-constanta-banci.json) | 3 | 3 KB | [CSV](ro-constanta-banci_RO.csv) | [Excel](ro-constanta-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-constanta-banci/) |
| [Bănci în Pitesti — coduri SWIFT/BIC](ro-pitesti-banci.json) | 3 | 3 KB | [CSV](ro-pitesti-banci_RO.csv) | [Excel](ro-pitesti-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-pitesti-banci/) |
| [Bănci în Roman — coduri SWIFT/BIC](ro-roman-banci.json) | 3 | 3 KB | [CSV](ro-roman-banci_RO.csv) | [Excel](ro-roman-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-roman-banci/) |
| [Bănci în Voluntari — coduri SWIFT/BIC](ro-voluntari-banci.json) | 3 | 3 KB | [CSV](ro-voluntari-banci_RO.csv) | [Excel](ro-voluntari-banci_RO.xlsx) | [View](https://listbase.org/ro/finance/ro-voluntari-banci/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.ro.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.ro.listbase.org/finance/ro-piete.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ro/finance/)
