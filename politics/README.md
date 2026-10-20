# Politik (Politics)

3 datasets — 302 records

> Browse at [listbase.org/da/politics/](https://listbase.org/da/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Politistationer i Danmark – OpenStreetMap (Police stations in Denmark, OSM)](da-politistationer.json) | 144 | 17 KB | [CSV](da-politistationer_DA.csv) | [Excel](da-politistationer_DA.xlsx) | [View](https://listbase.org/da/politics/da-politistationer/) |
| [Rådhuse i Danmark – OpenStreetMap (Town halls in Denmark, OSM)](da-raadhuse.json) | 116 | 13 KB | [CSV](da-raadhuse_DA.csv) | [Excel](da-raadhuse_DA.xlsx) | [View](https://listbase.org/da/politics/da-raadhuse/) |
| [Danmarks statsministre](da-statsministre.json) | 42 | 28 KB | [CSV](da-statsministre_DA.csv) | [Excel](da-statsministre_DA.xlsx) | [View](https://listbase.org/da/politics/da-statsministre/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/politics/da-politistationer.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/politics/)
