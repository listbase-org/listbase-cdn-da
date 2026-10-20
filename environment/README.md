# Miljø (Environment)

7 datasets — 621 records

> Browse at [listbase.org/da/environment/](https://listbase.org/da/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kraftværker i Danmark](da-kraftvaerker.json) | 368 | 187 KB | [CSV](da-kraftvaerker_DA.csv) | [Excel](da-kraftvaerker_DA.xlsx) | [View](https://listbase.org/da/environment/da-kraftvaerker/) |
| [Solkraftværker (solcelleanlæg) i Danmark](da-solkraftvaerker.json) | 206 | 105 KB | [CSV](da-solkraftvaerker_DA.csv) | [Excel](da-solkraftvaerker_DA.xlsx) | [View](https://listbase.org/da/environment/da-solkraftvaerker/) |
| [Måleenheder: energy (14)](da-maaleenheder-energy.json) | 14 | 5 KB | [CSV](da-maaleenheder-energy_DA.csv) | [Excel](da-maaleenheder-energy_DA.xlsx) | [View](https://listbase.org/da/environment/da-maaleenheder-energy/) |
| [Biokraftværker (fast biomasse) i Danmark](da-biokraftvaerker.json) | 10 | 8 KB | [CSV](da-biokraftvaerker_DA.csv) | [Excel](da-biokraftvaerker_DA.xlsx) | [View](https://listbase.org/da/environment/da-biokraftvaerker/) |
| [Kulkraftværker (stenkul) i Danmark](da-kulkraftvaerker.json) | 10 | 9 KB | [CSV](da-kulkraftvaerker_DA.csv) | [Excel](da-kulkraftvaerker_DA.xlsx) | [View](https://listbase.org/da/environment/da-kulkraftvaerker/) |
| [Batterilagre (energilagring) i Danmark](da-batterilager.json) | 8 | 7 KB | [CSV](da-batterilager_DA.csv) | [Excel](da-batterilager_DA.xlsx) | [View](https://listbase.org/da/environment/da-batterilager/) |
| [Måleenheder: temperature (5)](da-maaleenheder-temperature.json) | 5 | 3 KB | [CSV](da-maaleenheder-temperature_DA.csv) | [Excel](da-maaleenheder-temperature_DA.xlsx) | [View](https://listbase.org/da/environment/da-maaleenheder-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/environment/da-kraftvaerker.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/environment/)
