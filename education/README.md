# Uddannelse (Education)

4 datasets — 4,279 records

> Browse at [listbase.org/da/education/](https://listbase.org/da/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Skoler i Danmark – OpenStreetMap (Schools in Denmark, OSM)](da-skoler.json) | 2,481 | 260 KB | [CSV](da-skoler_DA.csv) | [Excel](da-skoler_DA.xlsx) | [View](https://listbase.org/da/education/da-skoler/) |
| [Børnehaver i Danmark – OpenStreetMap (Kindergartens in Denmark, OSM)](da-boernehaver.json) | 1,616 | 172 KB | [CSV](da-boernehaver_DA.csv) | [Excel](da-boernehaver_DA.xlsx) | [View](https://listbase.org/da/education/da-boernehaver/) |
| [Gymnasier i Danmark](da-gymnasier.json) | 148 | 207 KB | [CSV](da-gymnasier_DA.csv) | [Excel](da-gymnasier_DA.xlsx) | [View](https://listbase.org/da/education/da-gymnasier/) |
| [Denmark — Universities (universiteter)](da-universiteter.json) | 34 | 11 KB | [CSV](da-universiteter_DA.csv) | [Excel](da-universiteter_DA.xlsx) | [View](https://listbase.org/da/education/da-universiteter/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/education/da-skoler.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/education/)
