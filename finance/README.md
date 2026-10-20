# Finans og handel (Finance & Trade)

4 datasets — 4,045 records

> Browse at [listbase.org/da/finance/](https://listbase.org/da/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Caféer i Danmark – OpenStreetMap (Cafés in Denmark, OSM)](da-cafeer.json) | 3,355 | 343 KB | [CSV](da-cafeer_DA.csv) | [Excel](da-cafeer_DA.xlsx) | [View](https://listbase.org/da/finance/da-cafeer/) |
| [SWIFT/BIC-koder — Danmark](da-swift-koder.json) | 611 | 84 KB | [CSV](da-swift-koder_DA.csv) | [Excel](da-swift-koder_DA.xlsx) | [View](https://listbase.org/da/finance/da-swift-koder/) |
| [Pengeautomater i Danmark – OpenStreetMap (ATMs in Denmark, OSM)](da-pengeautomater.json) | 67 | 8 KB | [CSV](da-pengeautomater_DA.csv) | [Excel](da-pengeautomater_DA.xlsx) | [View](https://listbase.org/da/finance/da-pengeautomater/) |
| [Naturgaskraftværker i Danmark](da-naturgaskraftvaerker.json) | 12 | 9 KB | [CSV](da-naturgaskraftvaerker_DA.csv) | [Excel](da-naturgaskraftvaerker_DA.xlsx) | [View](https://listbase.org/da/finance/da-naturgaskraftvaerker/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/finance/da-cafeer.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/finance/)
