# Sant Pere, Slowly

A minimalist Hugo field guide to Sant Pere and Santa Caterina in Barcelona, with a photo led place guide, an interactive map, and a weekly local reading list.

## Local preview

Install Hugo, then run:

```sh
hugo server
```

## Weekly digest

The newest dated digest lives in `content/news/`; the homepage shows only the latest issue and older files remain available as an archive. The ready-to-schedule Codex prompt and cadence are in `codex-weekly-news-task.md`.

## Map

The interactive map uses Leaflet and OpenStreetMap tiles. Place data lives in `data/places.json`.

## Photography

Location photographs are stored in `static/images/`. Each image caption on the site links to its Wikimedia Commons source and license; the photos are shared under the linked Creative Commons terms.

## Place pages

Each stop has its own Hugo content page under `content/places/`. The homepage index and interactive map link directly to these pages.
