# Teknologi (Technology)

14 datasets — 3,301 records

> Browse at [listbase.org/da/tech/](https://listbase.org/da/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emoji danske navne (CLDR, 1966)](da-emoji-navne.json) | 1,966 | 290 KB | [CSV](da-emoji-navne_DA.csv) | [Excel](da-emoji-navne_DA.xlsx) | [View](https://listbase.org/da/tech/da-emoji-navne/) |
| [Biblioteker i Danmark](da-bibliotek.json) | 679 | 642 KB | [CSV](da-bibliotek_DA.csv) | [Excel](da-bibliotek_DA.xlsx) | [View](https://listbase.org/da/tech/da-bibliotek/) |
| [Emoji-flag for lande](da-lande-emoji-flag.json) | 252 | 39 KB | [CSV](da-lande-emoji-flag_DA.csv) | [Excel](da-lande-emoji-flag_DA.xlsx) | [View](https://listbase.org/da/tech/da-lande-emoji-flag/) |
| [Skriftsystemer (ISO 15924 / CLDR, 168)](da-skriftsystemer.json) | 168 | 14 KB | [CSV](da-skriftsystemer_DA.csv) | [Excel](da-skriftsystemer_DA.xlsx) | [View](https://listbase.org/da/tech/da-skriftsystemer/) |
| [Tidszoner (CLDR da, 118)](da-tidszoner.json) | 118 | 21 KB | [CSV](da-tidszoner_DA.csv) | [Excel](da-tidszoner_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner/) |
| [Tidszoner: America (43)](da-tidszoner-america.json) | 43 | 9 KB | [CSV](da-tidszoner-america_DA.csv) | [Excel](da-tidszoner-america_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-america/) |
| [Tidszoner: Asia (26)](da-tidszoner-asia.json) | 26 | 5 KB | [CSV](da-tidszoner-asia_DA.csv) | [Excel](da-tidszoner-asia_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-asia/) |
| [Tidszoner: Europe (20)](da-tidszoner-europe.json) | 20 | 4 KB | [CSV](da-tidszoner-europe_DA.csv) | [Excel](da-tidszoner-europe_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-europe/) |
| [Tidszoner: Pacific (8)](da-tidszoner-pacific.json) | 8 | 3 KB | [CSV](da-tidszoner-pacific_DA.csv) | [Excel](da-tidszoner-pacific_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-pacific/) |
| [Tidszoner: Africa (7)](da-tidszoner-africa.json) | 7 | 2 KB | [CSV](da-tidszoner-africa_DA.csv) | [Excel](da-tidszoner-africa_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-africa/) |
| [Tidszoner: Atlantic (5)](da-tidszoner-atlantic.json) | 5 | 2 KB | [CSV](da-tidszoner-atlantic_DA.csv) | [Excel](da-tidszoner-atlantic_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-atlantic/) |
| [Tidszoner: Indian (5)](da-tidszoner-indian.json) | 5 | 2 KB | [CSV](da-tidszoner-indian_DA.csv) | [Excel](da-tidszoner-indian_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-indian/) |
| [Tidszoner: Antarctica (2)](da-tidszoner-antarctica.json) | 2 | 2 KB | [CSV](da-tidszoner-antarctica_DA.csv) | [Excel](da-tidszoner-antarctica_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-antarctica/) |
| [Tidszoner: Etc (2)](da-tidszoner-etc.json) | 2 | 2 KB | [CSV](da-tidszoner-etc_DA.csv) | [Excel](da-tidszoner-etc_DA.xlsx) | [View](https://listbase.org/da/tech/da-tidszoner-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/tech/da-emoji-navne.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/tech/)
