# Gokwe South Schools & Clinics Access Dashboard

An interactive, deploy-ready web GIS dashboard for Gokwe South District, Midlands Province, Zimbabwe. It has interactive facility layers, map editing/drawing controls, removal controls, search queries and browser-based persistence for new field records.

## Data transparency

- The dashboard reports 190 schools and 40 clinics from the Gokwe South RDC 2025 annual targets report; that report says 24 clinics were functional at its reporting time.
- The displayed named facility points are limited OpenStreetMap-derived reference locations. They are not a complete official facility registry and must be field-verified before operational decisions.
- The displayed Gokwe South extent follows the public district bounding box. The supplied ZIMSTAT/OCHA administrative GDB should be imported as the precise district geometry after approved access to that data.

## Run locally

Requires Node 18+.

```bash
npm start
```

Open http://localhost:10000.

## Deploy to Render

Push this folder to GitHub. In Render choose **New → Blueprint**, select the repository, and Render will use `render.yaml`. No environment variables are required.
