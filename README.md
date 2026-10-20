# ListBase CDN — Română (ro)

Open dataset collection for **Română** (Romanian).
414 datasets across 12 categories with 160,595 total records.

> Browse and download at [https://listbase.org/ro/](https://listbase.org/ro/)

## Categories

| Category | Datasets |
|----------|----------|
| [Cultură și religie (Culture & Religion)](culture/) | 3 |
| [Educație (Education)](education/) | 46 |
| [Divertisment (Entertainment)](entertainment/) | 10 |
| [Mediu (Environment)](environment/) | 2 |
| [Finanțe și comerț (Finance & Trade)](finance/) | 15 |
| [Alimentație (Food & Nutrition)](food/) | 2 |
| [Geografie (Geography)](geography/) | 93 |
| [Referință (Reference)](reference/) | 192 |
| [Sport (Sports)](sports/) | 1 |
| [Timp și calendar (Time & Calendar)](time/) | 2 |
| [Turism (Tourism)](tourism/) | 2 |
| [Transport](transport/) | 46 |

## Usage

### Browse on the web
Visit [listbase.org/ro/](https://listbase.org/ro/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.ro.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.ro.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.ro.listbase.org/geography/th-central-provinces_RO.xlsx
curl -O https://cdn.ro.listbase.org/geography/th-central-provinces_RO.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.ro.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.ro.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_RO.csv   # CSV download
│   └── {dataset}_RO.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
