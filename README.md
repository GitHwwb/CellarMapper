# CellarMapper

Visualize your wine collection on an interactive world map with terroir overlays, tasting notes, and charts.

**[Live Demo →](https://yourusername.github.io/cellarmapper/)** *(update this URL after deploying)*

## Features
- Upload a CSV from CellarTracker, Vivino, or any wine app
- World map with markers colored by wine type (red/white/rosé)
- Multi-select filters by varietal, dynamically generated from your data
- Geology, soil, climate, elevation, and satellite overlays
- Click-to-query geology (Macrostrat) and soil type (ISRIC SoilGrids)
- Live terroir descriptions in every wine popup
- Split view for comparing two regions side by side
- Expandable charts: by country, top varietals, consumption timeline
- Fullscreen mode with overlay controls
- All data stays in your browser — nothing is uploaded to any server

## How to Use
1. Visit the site
2. Export your wine data as CSV from CellarTracker or Vivino
3. Drag and drop the CSV onto the page
4. Explore your wines on the map

## How to Export Your Data

**CellarTracker:** Log in → My Cellar → List View → Download (CSV)

**Vivino:** Use the [Vivino Exporter](https://github.com/sulfo/Vivino-Exporter) browser extension

**Other apps:** Any CSV with columns like Wine, Vintage, Country, Region, Varietal will work

## Tech
- Leaflet.js for maps
- CartoDB dark tiles
- Macrostrat API for geology
- ISRIC SoilGrids WMS for soil data
- CORINE Land Cover for European vineyard mapping
- Zero dependencies, zero backend, single HTML file

## License
MIT

---

<a href="https://www.buymeacoffee.com/Jon.L" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
