# Transport (Transport)

11 datasets — 1,695 records

> Browse at [listbase.org/da/transport/](https://listbase.org/da/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [UN/LOCODE-stedkoder — Danmark (havne, lufthavne, terminaler)](da-unlocode.json) | 754 | 484 KB | [CSV](da-unlocode_DA.csv) | [Excel](da-unlocode_DA.xlsx) | [View](https://listbase.org/da/transport/da-unlocode/) |
| [Ladestationer (elbil) i Danmark – OpenStreetMap (EV charging stations in Denmark, OSM)](da-ladestationer.json) | 684 | 71 KB | [CSV](da-ladestationer_DA.csv) | [Excel](da-ladestationer_DA.xlsx) | [View](https://listbase.org/da/transport/da-ladestationer/) |
| [IATA/ICAO-koder for lufthavne i Danmark, Grønland og Færøerne](da-iata-icao-lufthavne.json) | 75 | 18 KB | [CSV](da-iata-icao-lufthavne_DA.csv) | [Excel](da-iata-icao-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-iata-icao-lufthavne/) |
| [Landingsbaner i Danmark](da-landingsbaner.json) | 61 | 53 KB | [CSV](da-landingsbaner_DA.csv) | [Excel](da-landingsbaner_DA.xlsx) | [View](https://listbase.org/da/transport/da-landingsbaner/) |
| [Lufthavne i Danmark](da-lufthavne.json) | 49 | 22 KB | [CSV](da-lufthavne_DA.csv) | [Excel](da-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-lufthavne/) |
| [Radionavigationshjælpemidler i Danmark](da-radionavigationshjaelp.json) | 23 | 20 KB | [CSV](da-radionavigationshjaelp_DA.csv) | [Excel](da-radionavigationshjaelp_DA.xlsx) | [View](https://listbase.org/da/transport/da-radionavigationshjaelp/) |
| [Lufthavne — Region Midtjylland](da-midtjylland-lufthavne.json) | 16 | 9 KB | [CSV](da-midtjylland-lufthavne_DA.csv) | [Excel](da-midtjylland-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-midtjylland-lufthavne/) |
| [Lufthavne — Region Syddanmark](da-syddanmark-lufthavne.json) | 12 | 7 KB | [CSV](da-syddanmark-lufthavne_DA.csv) | [Excel](da-syddanmark-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-syddanmark-lufthavne/) |
| [Lufthavne — Region Sjælland](da-sjaelland-lufthavne.json) | 10 | 6 KB | [CSV](da-sjaelland-lufthavne_DA.csv) | [Excel](da-sjaelland-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-sjaelland-lufthavne/) |
| [Lufthavne — Region Nordjylland](da-nordjylland-lufthavne.json) | 8 | 6 KB | [CSV](da-nordjylland-lufthavne_DA.csv) | [Excel](da-nordjylland-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-nordjylland-lufthavne/) |
| [Lufthavne — Region Hovedstaden](da-hovedstaden-lufthavne.json) | 3 | 4 KB | [CSV](da-hovedstaden-lufthavne_DA.csv) | [Excel](da-hovedstaden-lufthavne_DA.xlsx) | [View](https://listbase.org/da/transport/da-hovedstaden-lufthavne/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/transport/da-unlocode.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/transport/)
