# Zimbabwe Agricultural GIS

An interactive, deploy-ready dashboard for exploring Zimbabwe's agricultural context. It displays provincial boundaries, an editable demonstration distribution of maize growers, query tools, and a local browser database.

## Data notes

- Provincial boundaries are simplified display geometries based on the Zimbabwe administrative-boundaries data published by the Zimbabwe geospatial community / ZIMSTAT (ODC-BY 1.0): https://zimgeoportal.org.zw/datasets/zimbabwe-administrative-boundaries/
- The 2025/26 national maize area shown in the dashboard is 1,898,528 hectares, from the Ministry of Lands, Agriculture, Fisheries, Water and Rural Development CLAFA-1 report: https://www.agric.gov.zw/wordpress/wp-content/uploads/2026/03/2026-CLAFA-1-REPORT.pdf
- Point features are **synthetic demonstration records** allocated by province. They are not farm coordinates or a farmer registry. Replace them with consented, verified field records before operational use.

## Run locally

Requires Node 18+.

```bash
npm start
```

Open http://localhost:10000.

## Deploy to Render

Push this folder to GitHub, then in Render choose **New → Blueprint** and select the repository. Render reads `render.yaml`; no environment variables are needed.
