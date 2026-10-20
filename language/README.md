# Sprog (Language)

2 datasets — 173 records

> Browse at [listbase.org/da/language/](https://listbase.org/da/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sprog efter ISO 639-1](da-sprog.json) | 115 | 21 KB | [CSV](da-sprog_DA.csv) | [Excel](da-sprog_DA.xlsx) | [View](https://listbase.org/da/language/da-sprog/) |
| [Sprogvarianter (BCP 47 / CLDR, 58)](da-sprogvarianter.json) | 58 | 6 KB | [CSV](da-sprogvarianter_DA.csv) | [Excel](da-sprogvarianter_DA.xlsx) | [View](https://listbase.org/da/language/da-sprogvarianter/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/language/da-sprog.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/language/)
