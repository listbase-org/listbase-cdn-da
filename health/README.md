# Sundhed (Health)

7 datasets — 1,609 records

> Browse at [listbase.org/da/health/](https://listbase.org/da/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Materialister i Danmark (Chemists and drugstores in Denmark)](da-materialister.json) | 438 | 42 KB | [CSV](da-materialister_DA.csv) | [Excel](da-materialister_DA.xlsx) | [View](https://listbase.org/da/health/da-materialister/) |
| [Optikere i Danmark (Opticians in Denmark)](da-optikere.json) | 350 | 35 KB | [CSV](da-optikere_DA.csv) | [Excel](da-optikere_DA.xlsx) | [View](https://listbase.org/da/health/da-optikere/) |
| [Læger og lægehuse i Danmark (Doctors and clinics in Denmark)](da-laeger.json) | 311 | 35 KB | [CSV](da-laeger_DA.csv) | [Excel](da-laeger_DA.xlsx) | [View](https://listbase.org/da/health/da-laeger/) |
| [Tandlæger i Danmark (Dentists in Denmark)](da-tandlaeger.json) | 273 | 31 KB | [CSV](da-tandlaeger_DA.csv) | [Excel](da-tandlaeger_DA.xlsx) | [View](https://listbase.org/da/health/da-tandlaeger/) |
| [Apoteker i Danmark – OpenStreetMap (Pharmacies in Denmark, OSM)](da-apoteker.json) | 140 | 16 KB | [CSV](da-apoteker_DA.csv) | [Excel](da-apoteker_DA.xlsx) | [View](https://listbase.org/da/health/da-apoteker/) |
| [Klinikker i Danmark (Clinics in Denmark)](da-klinikker.json) | 62 | 8 KB | [CSV](da-klinikker_DA.csv) | [Excel](da-klinikker_DA.xlsx) | [View](https://listbase.org/da/health/da-klinikker/) |
| [Hospitaler i Danmark – OpenStreetMap (Hospitals in Denmark, OSM)](da-hospitaler.json) | 35 | 5 KB | [CSV](da-hospitaler_DA.csv) | [Excel](da-hospitaler_DA.xlsx) | [View](https://listbase.org/da/health/da-hospitaler/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/health/da-materialister.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/health/)
