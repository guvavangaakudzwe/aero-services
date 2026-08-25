# Zimbabwe AeroGIS

An interactive Leaflet dashboard for viewing Zimbabwe's official district boundaries, supplied major-town data, and the supplied WGS84 aeronautical chart.

## Included source data

- `public/districts.geojson`: 91 district boundaries converted from the supplied ZIMSTAT/OCHA 2018 geodatabase.
- `public/major-towns.geojson`: seven major towns converted from the supplied shapefile archive.
- `public/aeronautical-chart.jpg`: the countrywide level-1 image from the supplied WGS84 aeronautical KMZ, placed as an optional georeferenced overlay.

Town cards link a town to its aerodrome reference. They intentionally do **not** claim live operational information. Check the current AIP and NOTAMs before flight planning or operational use.

## Run and deploy

Requires Node 18+.

```bash
npm start
```

Use Render’s **New → Blueprint** flow after pushing the project to GitHub. `render.yaml` provides the service configuration.
