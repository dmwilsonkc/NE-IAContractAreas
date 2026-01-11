# NE-IA Contract Areas Map

## Project Overview

Interactive web map displaying union contract jurisdictions for three carpenter/millwright union locals in Nebraska, Iowa, and South Dakota. Built for the Mid-America Carpenters Regional Council.

**Live Site**: https://dmwilsonkc.github.io/NE-IAContractAreas/

## Union Locals Covered

- **Carpenters LU 427**: Split into Metro Agreement (22 NE + 9 IA counties) and Lincoln/Outstate Agreement (71 NE counties)
- **Interior Systems LU 1306**: All NE counties except Cedar, Dakota, Dixon, Thurston + 9 IA counties
- **Millwright LU 1463**: All 93 NE counties + 52 IA counties + Union County, SD

## Tech Stack

- **Leaflet.js 1.9.4** - Interactive mapping library (loaded from CDN)
- **OpenStreetMap** - Base map tiles
- **GeoJSON** - County boundary data loaded from plotly datasets CDN
- **Vanilla HTML/CSS/JS** - No build system, no dependencies to install

## File Structure

```
index.html      # Main application (all code in single file)
test-map.html   # Leaflet testing page
README.md       # User documentation
LICENSE         # MIT License
```

## Key Data Structures in index.html

- `lu427MetroCounties[]` - County list for LU 427 Metro Agreement
- `lu427OutstateCounties[]` - County list for LU 427 Lincoln/Outstate
- `lu1306ExcludedNE[]` - NE counties excluded from LU 1306
- `lu1306IowaCounties[]` - IA counties in LU 1306
- `lu1463IowaCounties[]` - IA counties in LU 1463
- `fipsToCounty{}` - FIPS code to "County, ST" mapping for NE/IA/SD

## County Key Format

Counties are referenced as `"County Name, ST"` (e.g., `"Douglas, NE"`, `"Pottawattamie, IA"`)

## Colors

- Metro (LU 427): `#2E86AB` (blue)
- Outstate (LU 427): `#A23B72` (purple)
- LU 1306: `#F18F01` (orange)
- LU 1463: `#6A994E` (green)

## Development

No build step required. Open `index.html` directly in a browser for local development.

## Deployment

Hosted on GitHub Pages. Push to `main` branch to deploy automatically.

## Contact Info (displayed on maps)

10761 Virginia Plaza, Papillion NE 68128
Phone: 402-571-2561
