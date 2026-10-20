# ListBase CDN — Dansk (da)

Open dataset collection for **Dansk** (Danish).
421 datasets across 19 categories with 234,802 total records.

> Browse and download at [https://listbase.org/da/](https://listbase.org/da/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultur og religion (Culture & Religion)](culture/) | 20 |
| [Uddannelse (Education)](education/) | 4 |
| [Underholdning (Entertainment)](entertainment/) | 3 |
| [Miljø (Environment)](environment/) | 7 |
| [Finans og handel (Finance & Trade)](finance/) | 4 |
| [Mad (Food & Nutrition)](food/) | 10 |
| [Geografi (Geography)](geography/) | 21 |
| [Sundhed (Health)](health/) | 7 |
| [Historie (History)](history/) | 2 |
| [Sprog (Language)](language/) | 2 |
| [Politik (Politics)](politics/) | 3 |
| [Reference](reference/) | 250 |
| [Samfund (Society)](society/) | 2 |
| [Sport (Sports)](sports/) | 2 |
| [Teknologi (Technology)](tech/) | 14 |
| [Tid og kalender (Time & Calendar)](time/) | 30 |
| [Turisme (Tourism)](tourism/) | 8 |
| [Transport](transport/) | 11 |
| [Enheder og mål (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/da/](https://listbase.org/da/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.da.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.da.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.da.listbase.org/geography/th-central-provinces_DA.xlsx
curl -O https://cdn.da.listbase.org/geography/th-central-provinces_DA.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.da.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.da.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_DA.csv   # CSV download
│   └── {dataset}_DA.xlsx  # Excel download
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
