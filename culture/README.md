# Kultur og religion (Culture & Religion)

20 datasets — 6,833 records

> Browse at [listbase.org/da/culture/](https://listbase.org/da/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Folkekirken — Danske kirker via da.wikipedia + Wikidata](da-folkekirken.json) | 1,746 | 5354 KB | [CSV](da-folkekirken_DA.csv) | [Excel](da-folkekirken_DA.xlsx) | [View](https://listbase.org/da/culture/da-folkekirken/) |
| [Forsamlings- og medborgerhuse i Danmark – OpenStreetMap (Community centres in Denmark, OSM)](da-forsamlingshuse.json) | 1,324 | 142 KB | [CSV](da-forsamlingshuse_DA.csv) | [Excel](da-forsamlingshuse_DA.xlsx) | [View](https://listbase.org/da/culture/da-forsamlingshuse/) |
| [[object Object]](da-herregaarde.json) | 788 | 1079 KB | [CSV](da-herregaarde_DA.csv) | [Excel](da-herregaarde_DA.xlsx) | [View](https://listbase.org/da/culture/da-herregaarde/) |
| [Beskyttede områder i Danmark](da-beskyttede-omraader.json) | 571 | 1130 KB | [CSV](da-beskyttede-omraader_DA.csv) | [Excel](da-beskyttede-omraader_DA.xlsx) | [View](https://listbase.org/da/culture/da-beskyttede-omraader/) |
| [Slotte i Danmark (Palaces and Castles of Denmark)](da-slotte.json) | 382 | 491 KB | [CSV](da-slotte_DA.csv) | [Excel](da-slotte_DA.xlsx) | [View](https://listbase.org/da/culture/da-slotte/) |
| [Mindesmærker i Danmark](da-mindesmaerker.json) | 354 | 65 KB | [CSV](da-mindesmaerker_DA.csv) | [Excel](da-mindesmaerker_DA.xlsx) | [View](https://listbase.org/da/culture/da-mindesmaerker/) |
| [Museer i Danmark – OpenStreetMap (Museums in Denmark, OSM)](da-osm-museer.json) | 329 | 72 KB | [CSV](da-osm-museer_DA.csv) | [Excel](da-osm-museer_DA.xlsx) | [View](https://listbase.org/da/culture/da-osm-museer/) |
| [Kirkegårde i Danmark – OpenStreetMap (Cemeteries / graveyards in Denmark, OSM)](da-kirkegaarde.json) | 309 | 34 KB | [CSV](da-kirkegaarde_DA.csv) | [Excel](da-kirkegaarde_DA.xlsx) | [View](https://listbase.org/da/culture/da-kirkegaarde/) |
| [Museer i Danmark](da-museer.json) | 247 | 308 KB | [CSV](da-museer_DA.csv) | [Excel](da-museer_DA.xlsx) | [View](https://listbase.org/da/culture/da-museer/) |
| [[object Object]](da-borge.json) | 235 | 124 KB | [CSV](da-borge_DA.csv) | [Excel](da-borge_DA.xlsx) | [View](https://listbase.org/da/culture/da-borge/) |
| [Teatre i Danmark – OpenStreetMap (Theatres in Denmark, OSM)](da-teatre.json) | 218 | 23 KB | [CSV](da-teatre_DA.csv) | [Excel](da-teatre_DA.xlsx) | [View](https://listbase.org/da/culture/da-teatre/) |
| [Fyrtårne i Danmark / Lighthouses of Denmark](da-fyrtarn.json) | 90 | 120 KB | [CSV](da-fyrtarn_DA.csv) | [Excel](da-fyrtarn_DA.xlsx) | [View](https://listbase.org/da/culture/da-fyrtarn/) |
| [Statuer i Danmark](da-statuer.json) | 72 | 16 KB | [CSV](da-statuer_DA.csv) | [Excel](da-statuer_DA.xlsx) | [View](https://listbase.org/da/culture/da-statuer/) |
| [Arkæologiske steder i Danmark](da-arkaeologiske-steder.json) | 65 | 14 KB | [CSV](da-arkaeologiske-steder_DA.csv) | [Excel](da-arkaeologiske-steder_DA.xlsx) | [View](https://listbase.org/da/culture/da-arkaeologiske-steder/) |
| [Vindmøller i Danmark](da-vindmoller.json) | 28 | 7 KB | [CSV](da-vindmoller_DA.csv) | [Excel](da-vindmoller_DA.xlsx) | [View](https://listbase.org/da/culture/da-vindmoller/) |
| [Klostre i Danmark](da-klostre.json) | 24 | 6 KB | [CSV](da-klostre_DA.csv) | [Excel](da-klostre_DA.xlsx) | [View](https://listbase.org/da/culture/da-klostre/) |
| [Domkirker i Danmark](da-domkirker.json) | 20 | 88 KB | [CSV](da-domkirker_DA.csv) | [Excel](da-domkirker_DA.xlsx) | [View](https://listbase.org/da/culture/da-domkirker/) |
| [Moskeer i Danmark](da-moskeer.json) | 14 | 4 KB | [CSV](da-moskeer_DA.csv) | [Excel](da-moskeer_DA.xlsx) | [View](https://listbase.org/da/culture/da-moskeer/) |
| [Verdensarv i Danmark](da-verdensarv-unesco.json) | 10 | 13 KB | [CSV](da-verdensarv-unesco_DA.csv) | [Excel](da-verdensarv-unesco_DA.xlsx) | [View](https://listbase.org/da/culture/da-verdensarv-unesco/) |
| [[object Object]](da-vikingeborge.json) | 7 | 63 KB | [CSV](da-vikingeborge_DA.csv) | [Excel](da-vikingeborge_DA.xlsx) | [View](https://listbase.org/da/culture/da-vikingeborge/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/culture/da-folkekirken.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/culture/)
