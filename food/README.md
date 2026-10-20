# Mad (Food & Nutrition)

10 datasets — 14,236 records

> Browse at [listbase.org/da/food/](https://listbase.org/da/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Fastfood-steder i Danmark – OpenStreetMap (Fast food outlets in Denmark, OSM)](da-fastfood.json) | 6,200 | 632 KB | [CSV](da-fastfood_DA.csv) | [Excel](da-fastfood_DA.xlsx) | [View](https://listbase.org/da/food/da-fastfood/) |
| [Restauranter i Danmark – OpenStreetMap (Restaurants in Denmark, OSM)](da-restauranter.json) | 3,091 | 313 KB | [CSV](da-restauranter_DA.csv) | [Excel](da-restauranter_DA.xlsx) | [View](https://listbase.org/da/food/da-restauranter/) |
| [Bagerier i Danmark – OpenStreetMap (Bakeries in Denmark, OSM)](da-bagerier.json) | 1,183 | 122 KB | [CSV](da-bagerier_DA.csv) | [Excel](da-bagerier_DA.xlsx) | [View](https://listbase.org/da/food/da-bagerier/) |
| [Slagtere i Danmark – OpenStreetMap (Butchers in Denmark, OSM)](da-slagtere.json) | 895 | 96 KB | [CSV](da-slagtere_DA.csv) | [Excel](da-slagtere_DA.xlsx) | [View](https://listbase.org/da/food/da-slagtere/) |
| [Gårdbutikker i Danmark (Farm shops in Denmark)](da-gaardbutikker.json) | 830 | 88 KB | [CSV](da-gaardbutikker_DA.csv) | [Excel](da-gaardbutikker_DA.xlsx) | [View](https://listbase.org/da/food/da-gaardbutikker/) |
| [Vin- og spiritusforretninger i Danmark (Liquor and wine shops in Denmark)](da-vinhandlere.json) | 737 | 76 KB | [CSV](da-vinhandlere_DA.csv) | [Excel](da-vinhandlere_DA.xlsx) | [View](https://listbase.org/da/food/da-vinhandlere/) |
| [Delikatesseforretninger i Danmark (Delicatessens in Denmark)](da-delikatesseforretninger.json) | 564 | 61 KB | [CSV](da-delikatesseforretninger_DA.csv) | [Excel](da-delikatesseforretninger_DA.xlsx) | [View](https://listbase.org/da/food/da-delikatesseforretninger/) |
| [Isbutikker i Danmark (Ice cream parlours in Denmark)](da-isbutikker.json) | 472 | 49 KB | [CSV](da-isbutikker_DA.csv) | [Excel](da-isbutikker_DA.xlsx) | [View](https://listbase.org/da/food/da-isbutikker/) |
| [Grønthandlere i Danmark (Greengrocers in Denmark)](da-groenthandlere.json) | 153 | 17 KB | [CSV](da-groenthandlere_DA.csv) | [Excel](da-groenthandlere_DA.xlsx) | [View](https://listbase.org/da/food/da-groenthandlere/) |
| [Michelin-restauranter i Danmark](da-michelin-restauranter.json) | 111 | 122 KB | [CSV](da-michelin-restauranter_DA.csv) | [Excel](da-michelin-restauranter_DA.xlsx) | [View](https://listbase.org/da/food/da-michelin-restauranter/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/food/da-fastfood.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/food/)
