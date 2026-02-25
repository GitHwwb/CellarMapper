# CellarMapper

Visualize your wine collection on an interactive world map with terroir overlays, tasting notes, and charts.

**[Try it here →](https://githwwb.github.io/CellarMapper/)**

## Features
- Upload a CSV from CellarTracker, Vivino, or any wine app
- World map with markers colored by wine type — dynamically generated from your data
- Multi-select filters by type and varietal, all built from your CSV
- Overlays: Geology, Soil, Climate, Elevation, Satellite, Cropland
- Click-to-query tooltips for geology (Macrostrat), soil (ISRIC SoilGrids), and land cover (CORINE)
- Live terroir descriptions in every wine popup
- Dynamic geocoding for any wine region worldwide (via OpenStreetMap Nominatim)
- Split view for comparing two map regions side by side
- Spiderfy markers — click overlapping markers to fan them out
- Charts: by country, top varietals, and consumption timeline with year dividers
- Fullscreen mode with overlay and filter controls
- All data stays in your browser — nothing is uploaded to any server

## How to Use
1. Visit the site
2. Export your wine data as CSV from CellarTracker or Vivino
3. Drag and drop the CSV onto the page
4. Explore your wines on the map

## How to Export Your Data

**CellarTracker:** Follow the official guide: [Exporting Data from CellarTracker](https://support.cellartracker.com/article/29-exporting-data)

**Vivino:** Use the [Vivino Exporter](https://github.com/sulfo/Vivino-Exporter) browser extension

**Other apps:** Any CSV with columns like Wine, Vintage, Country, Region, Varietal, Type/Color will work. Unknown columns are handled gracefully.

## Overlays

| Overlay | Source | Click-to-query |
|---------|--------|----------------|
| Geology | [Macrostrat](https://macrostrat.org) carto tiles | Formation name, period, age, lithology, color swatch, link to Macrostrat |
| Soil | [ISRIC SoilGrids](https://soilgrids.org) WMS | WRB soil class with wine-relevance notes (official ISRIC colors) |
| Cropland | [CORINE Land Cover 2018](https://land.copernicus.eu) (EEA) | Land cover class with official EEA color swatch (Europe only) |
| Climate | Esri World Physical Map | — |
| Elevation | OpenTopoMap | — |
| Satellite | Esri World Imagery | — |

## Tech
- Leaflet.js for maps
- CartoDB dark tiles
- Macrostrat API for geology
- ISRIC SoilGrids WMS for soil data
- CORINE Land Cover 2018 WMS for European land cover
- OpenStreetMap Nominatim for dynamic geocoding
- Zero dependencies, zero backend, single HTML file

## License
All rights reserved. This project is shared for personal and educational use. Please do not redistribute or use commercially without permission.
