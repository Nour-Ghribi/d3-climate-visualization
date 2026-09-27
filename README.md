# D3 Climate Visualization

Interactive D3.js scrollytelling project about climate change, CO2 concentration, global temperature anomalies, and country-level temperature anomaly maps.

## Overview

This project turns climate time-series and geospatial data into an interactive visual narrative. It combines:

- an animated SVG climate metaphor,
- a CO2 time-series chart,
- scroll-driven transitions,
- hover tooltips,
- filter controls,
- a world choropleth map,
- country and regional statistics by period.

## Technologies

- HTML
- CSS
- JavaScript
- D3.js v7
- CSV and GeoJSON data

## Data

The project uses:

- `data/co2.csv` for annual CO2 concentration,
- `data/gistemp.csv` for global temperature anomaly,
- `data/country_temperature_anomaly.csv` for country-level anomaly values,
- `data/world-countries.geojson` for country geometries.

## Run Locally

Because the visualization loads CSV and GeoJSON files with `fetch`, it must be served through a local HTTP server.

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Relevance

This project demonstrates interactive data visualization skills with D3.js, including visual encoding, interaction design, map-based data exploration, and narrative visualization. It can support applications for visual analytics and data visualization internships.
