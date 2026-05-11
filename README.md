# irish-elections-viewer

This repository contains a browser-viewable SQLite database derived from the *Irish Elections, 1692–1800* dataset.

The database is intended for exploratory browsing and searching using Datasette.

## Online viewer

Open the browser-based searchable database here:

[Launch Irish Elections Viewer](https://lite.datasette.io/?url=https://raw.githubusercontent.com/forbess1/irish-elections-viewer/main/irish_elections_viewer.db)

## Files

- `irish_elections_viewer.db`

The database contains two main tables:

- `all_events`
- `petitions`

The `petitions` table links to associated election events through the `event_id` field.

## Source data

The canonical archival CSV datasets are available via the Open University ORDO repository:

https://doi.org/10.21954/ou.rd.30851183.v1

## Licence

CC BY-NC-ND 4.0
