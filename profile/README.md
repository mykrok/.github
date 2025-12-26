# MyKrok

> In Ukrainian **крок** (krok) is a "step". Together with English **My** they reflect my American identity with Ukrainian heritage. 

**MyKrok** is a CLI tool for backing up Strava activities with incremental sync, map visualization, and FitTrackee export.

## Features

- **Incremental backup** - Only downloads new activities since last sync
- **Complete data** - GPS tracks (Parquet), photos, comments, kudos, gear
- **Interactive map browser** - Explore your activities on a map
- **FitTrackee export** - Push your data to self-hosted FitTrackee
- **Privacy first** - Your data stays on your machine

## Quick Start

```bash
pip install mykrok
mykrok auth
mykrok sync
mykrok create-browser --serve
```

## Links

- [Documentation](https://github.com/mykrok/mykrok#readme)
- [PyPI](https://pypi.org/project/mykrok/)

---

*Your fitness journey, one step at a time.*
