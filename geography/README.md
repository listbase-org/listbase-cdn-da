# Geografi (Geography)

21 datasets — 2,189 records

> Browse at [listbase.org/da/geography/](https://listbase.org/da/geography/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Danske byer](da-byer.json) | 345 | 83 KB | [CSV](da-byer_DA.csv) | [Excel](da-byer_DA.xlsx) | [View](https://listbase.org/da/geography/da-byer/) |
| [Broer i Danmark](da-broer.json) | 277 | 354 KB | [CSV](da-broer_DA.csv) | [Excel](da-broer_DA.xlsx) | [View](https://listbase.org/da/geography/da-broer/) |
| [Landekoder (internationale telefonkoder)](da-landekode.json) | 258 | 111 KB | [CSV](da-landekode_DA.csv) | [Excel](da-landekode_DA.xlsx) | [View](https://listbase.org/da/geography/da-landekode/) |
| [Lande i verden (Danish country list)](da-lande.json) | 252 | 123 KB | [CSV](da-lande_DA.csv) | [Excel](da-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-lande/) |
| [Verdens lande](da-lande-verden.json) | 249 | 26 KB | [CSV](da-lande-verden_DA.csv) | [Excel](da-lande-verden_DA.xlsx) | [View](https://listbase.org/da/geography/da-lande-verden/) |
| [Øer i Danmark](da-oer.json) | 228 | 42 KB | [CSV](da-oer_DA.csv) | [Excel](da-oer_DA.xlsx) | [View](https://listbase.org/da/geography/da-oer/) |
| [Halvøer i Danmark](da-halvoer.json) | 108 | 21 KB | [CSV](da-halvoer_DA.csv) | [Excel](da-halvoer_DA.xlsx) | [View](https://listbase.org/da/geography/da-halvoer/) |
| [Strande i Danmark](da-strande.json) | 86 | 18 KB | [CSV](da-strande_DA.csv) | [Excel](da-strande_DA.xlsx) | [View](https://listbase.org/da/geography/da-strande/) |
| [Danske og rigsfællesskabsfjorde (Danish Realm Fjords)](da-fjorde.json) | 68 | 124 KB | [CSV](da-fjorde_DA.csv) | [Excel](da-fjorde_DA.xlsx) | [View](https://listbase.org/da/geography/da-fjorde/) |
| [Lande — Afrika](da-afrika-lande.json) | 60 | 31 KB | [CSV](da-afrika-lande_DA.csv) | [Excel](da-afrika-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-afrika-lande/) |
| [Lande — Asien](da-asien-lande.json) | 53 | 27 KB | [CSV](da-asien-lande_DA.csv) | [Excel](da-asien-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-asien-lande/) |
| [Lande — Europa](da-europa-lande.json) | 52 | 27 KB | [CSV](da-europa-lande_DA.csv) | [Excel](da-europa-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-europa-lande/) |
| [Lande — Nordamerika](da-nordamerika-lande.json) | 41 | 22 KB | [CSV](da-nordamerika-lande_DA.csv) | [Excel](da-nordamerika-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-nordamerika-lande/) |
| [Lande — Oceanien](da-oceanien-lande.json) | 27 | 15 KB | [CSV](da-oceanien-lande_DA.csv) | [Excel](da-oceanien-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-oceanien-lande/) |
| [Populære fornavne i Danmark (Popular Danish First Names)](da-fornavne.json) | 24 | 5 KB | [CSV](da-fornavne_DA.csv) | [Excel](da-fornavne_DA.xlsx) | [View](https://listbase.org/da/geography/da-fornavne/) |
| [Mest udbredte efternavne i Danmark (Popular Danish Surnames)](da-efternavne.json) | 20 | 4 KB | [CSV](da-efternavne_DA.csv) | [Excel](da-efternavne_DA.xlsx) | [View](https://listbase.org/da/geography/da-efternavne/) |
| [Lande — Sydamerika](da-sydamerika-lande.json) | 14 | 9 KB | [CSV](da-sydamerika-lande_DA.csv) | [Excel](da-sydamerika-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-sydamerika-lande/) |
| [Vandfald i Danmark, Grønland og Færøerne](da-vandfald.json) | 10 | 10 KB | [CSV](da-vandfald_DA.csv) | [Excel](da-vandfald_DA.xlsx) | [View](https://listbase.org/da/geography/da-vandfald/) |
| [Verdensdele (kontinenter)](da-verdensdele.json) | 7 | 2 KB | [CSV](da-verdensdele_DA.csv) | [Excel](da-verdensdele_DA.xlsx) | [View](https://listbase.org/da/geography/da-verdensdele/) |
| [Lande — Antarktis](da-antarktis-lande.json) | 5 | 5 KB | [CSV](da-antarktis-lande_DA.csv) | [Excel](da-antarktis-lande_DA.xlsx) | [View](https://listbase.org/da/geography/da-antarktis-lande/) |
| [Regioner i Danmark](da-regioner.json) | 5 | 3 KB | [CSV](da-regioner_DA.csv) | [Excel](da-regioner_DA.xlsx) | [View](https://listbase.org/da/geography/da-regioner/) |

## Quick Start

```bash
# List all geography datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="geography") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/geography/da-byer.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/geography/)
