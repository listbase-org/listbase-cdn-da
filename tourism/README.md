# Turisme (Tourism)

8 datasets — 3,125 records

> Browse at [listbase.org/da/tourism/](https://listbase.org/da/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Campingpladser i Danmark – OpenStreetMap (Campsites in Denmark, OSM)](da-campingpladser.json) | 1,210 | 131 KB | [CSV](da-campingpladser_DA.csv) | [Excel](da-campingpladser_DA.xlsx) | [View](https://listbase.org/da/tourism/da-campingpladser/) |
| [Hoteller i Danmark – OpenStreetMap (Hotels in Denmark, OSM)](da-hoteller.json) | 783 | 82 KB | [CSV](da-hoteller_DA.csv) | [Excel](da-hoteller_DA.xlsx) | [View](https://listbase.org/da/tourism/da-hoteller/) |
| [Turistattraktioner i Danmark – OpenStreetMap (Tourist attractions in Denmark, OSM)](da-attraktioner.json) | 465 | 48 KB | [CSV](da-attraktioner_DA.csv) | [Excel](da-attraktioner_DA.xlsx) | [View](https://listbase.org/da/tourism/da-attraktioner/) |
| [Gæstehuse i Danmark (Guest houses in Denmark)](da-gaestehuse.json) | 395 | 42 KB | [CSV](da-gaestehuse_DA.csv) | [Excel](da-gaestehuse_DA.xlsx) | [View](https://listbase.org/da/tourism/da-gaestehuse/) |
| [Udsigtspunkter i Danmark – OpenStreetMap (Viewpoints in Denmark, OSM)](da-udsigtspunkter.json) | 222 | 23 KB | [CSV](da-udsigtspunkter_DA.csv) | [Excel](da-udsigtspunkter_DA.xlsx) | [View](https://listbase.org/da/tourism/da-udsigtspunkter/) |
| [Zoologiske haver i Danmark](da-zoologiske-haver.json) | 26 | 6 KB | [CSV](da-zoologiske-haver_DA.csv) | [Excel](da-zoologiske-haver_DA.xlsx) | [View](https://listbase.org/da/tourism/da-zoologiske-haver/) |
| [Forlystelsesparker i Danmark](da-forlystelsesparker.json) | 16 | 4 KB | [CSV](da-forlystelsesparker_DA.csv) | [Excel](da-forlystelsesparker_DA.xlsx) | [View](https://listbase.org/da/tourism/da-forlystelsesparker/) |
| [Botaniske haver i Danmark](da-botaniske-haver.json) | 8 | 3 KB | [CSV](da-botaniske-haver_DA.csv) | [Excel](da-botaniske-haver_DA.xlsx) | [View](https://listbase.org/da/tourism/da-botaniske-haver/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/tourism/da-campingpladser.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/tourism/)
