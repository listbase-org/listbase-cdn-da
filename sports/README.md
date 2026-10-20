# Sport (Sports)

2 datasets — 308 records

> Browse at [listbase.org/da/sports/](https://listbase.org/da/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sportsbutikker i Danmark (Sports shops in Denmark)](da-sportsbutikker.json) | 256 | 26 KB | [CSV](da-sportsbutikker_DA.csv) | [Excel](da-sportsbutikker_DA.xlsx) | [View](https://listbase.org/da/sports/da-sportsbutikker/) |
| [Stadioner i Danmark](da-stadioner.json) | 52 | 11 KB | [CSV](da-stadioner_DA.csv) | [Excel](da-stadioner_DA.xlsx) | [View](https://listbase.org/da/sports/da-stadioner/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.da.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.da.listbase.org/sports/da-sportsbutikker.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/da/sports/)
