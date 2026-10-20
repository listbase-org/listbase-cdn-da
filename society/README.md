# Samfund (Society)

2 datasets — 830 records

> Browse at [listbase.org/da/society/](https://listbase.org/da/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Genbrugs- og velgørenhedsbutikker i Danmark (Charity and second-hand shops in Denmark)](da-genbrugsbutikker.json) | 818 | 87 KB | [CSV](da-genbrugsbutikker_DA.csv) | [Excel](da-genbrugsbutikker_DA.xlsx) | [View](https://listbase.org/da/society/da-genbrugsbutikker/) |
| [Politikredse i Danmark](da-politikredse.json) | 12 | 4 KB | [CSV](da-politikredse_DA.csv) | [Excel](da-politikredse_DA.xlsx) | [View](https://listbase.org/da/society/da-politikredse/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/society/da-genbrugsbutikker.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/society/)
