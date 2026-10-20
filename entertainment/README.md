# Underholdning (Entertainment)

3 datasets — 442 records

> Browse at [listbase.org/da/entertainment/](https://listbase.org/da/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Boghandlere i Danmark (Bookshops in Denmark)](da-boghandlere.json) | 194 | 21 KB | [CSV](da-boghandlere_DA.csv) | [Excel](da-boghandlere_DA.xlsx) | [View](https://listbase.org/da/entertainment/da-boghandlere/) |
| [Biografer i Danmark – OpenStreetMap (Cinemas in Denmark, OSM)](da-biografer.json) | 164 | 18 KB | [CSV](da-biografer_DA.csv) | [Excel](da-biografer_DA.xlsx) | [View](https://listbase.org/da/entertainment/da-biografer/) |
| [Danske tv-kanaler](da-tv-kanaler.json) | 84 | 31 KB | [CSV](da-tv-kanaler_DA.csv) | [Excel](da-tv-kanaler_DA.xlsx) | [View](https://listbase.org/da/entertainment/da-tv-kanaler/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/entertainment/da-boghandlere.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/entertainment/)
