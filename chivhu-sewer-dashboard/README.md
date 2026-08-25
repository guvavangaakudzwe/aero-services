# Chivhu Sewer Network GIS

Interactive map dashboard for the supplied Chivhu sewer network layers.

## Included data

- 47,362 sewer line features
- 25,995 sewer point features
- 1,483 manhole features

The source Shapefiles are retained under `data/source`; the dashboard reads full WGS84 GeoJSON copies from `public`.

## Run locally

Requires Node 18+:

```bash
npm start
```

Open `http://localhost:10000`.

## Deploy to Render

Create a Render Static Site and set the **Root Directory** to `chivhu-sewer-dashboard`, with **Publish Directory** `public`. Or point a Blueprint deployment at `chivhu-sewer-dashboard/render.yaml`.
