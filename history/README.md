# Historie (History)

2 datasets — 137 records

> Browse at [listbase.org/da/history/](https://listbase.org/da/history/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Vikingeskibe](da-vikingeskibe.json) | 69 | 398 KB | [CSV](da-vikingeskibe_DA.csv) | [Excel](da-vikingeskibe_DA.xlsx) | [View](https://listbase.org/da/history/da-vikingeskibe/) |
| [Danske monarker (konger og dronninger af Danmark)](da-monarki.json) | 68 | 73 KB | [CSV](da-monarki_DA.csv) | [Excel](da-monarki_DA.xlsx) | [View](https://listbase.org/da/history/da-monarki/) |

## Quick Start

```bash
# List all history datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="history") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/history/da-vikingeskibe.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/history/)
