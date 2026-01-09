# Union Contract Jurisdictions Map

An interactive web map showing the contract jurisdictions for:
- **Carpenters LU 427** (Metro Agreement & Lincoln/Outstate Agreement)
- **Interior Systems LU 1306**
- **Millwright LU 1463**

## Features

- **Interactive Map**: Click on any county to see which agreement covers it
- **Color-Coded Jurisdictions**: Each agreement has a distinct color for easy identification
- **Print-Friendly**: Optimized layout for printing with a print button
- **Responsive Design**: Works on desktop and mobile devices
- **Hover Effects**: Counties highlight when you hover over them

## Viewing the Map

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Your map will be available at: `https://[your-username].github.io/[repository-name]/`

### Option 2: Local Viewing

Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

## How to Use

1. **Zoom**: Use the +/- buttons or scroll wheel to zoom in/out
2. **Pan**: Click and drag to move around the map
3. **View Details**: Click on any county to see its agreement information
4. **Print**: Click the "🖨️ Print Map" button in the top-right corner

## Color Legend

- 🔵 **Blue** - Carpenters LU 427 Metro Agreement
- 🟣 **Purple** - Carpenters LU 427 Lincoln & Outstate Agreement
- 🟠 **Orange** - Interior Systems LU 1306
- 🟢 **Green** - Millwright LU 1463

## Agreement Coverage

### Carpenters LU 427 - Metro Agreement
**Nebraska Counties**: Antelope, Boone, Burt, Butler, Cass, Colfax, Cuming, Dodge, Douglas, Knox, Madison, Merrick, Nance, Otoe, Pierce, Platte, Polk, Sarpy, Saunders, Stanton, Washington, Wayne

**Iowa Counties**: Audubon, Cass, Fremont, Harrison, Mills, Montgomery, Page, Pottawattamie, Shelby

### Carpenters LU 427 - Lincoln & Outstate Agreement
All remaining Nebraska counties not covered by the Metro Agreement

### Interior Systems LU 1306
**Nebraska**: Entire state EXCEPT Cedar, Dakota, Dixon, and Thurston counties

**Iowa**: Audubon, Cass, Fremont, Harrison, Mills, Montgomery, Page, Pottawattamie, Shelby

### Millwright LU 1463
**Nebraska**: Entire state

**Iowa**: 52 counties (see full list in map popups)

**South Dakota**: Union County

## Contact Information

**Local Office**: 10761 Virginia Plaza, Papillion NE 68128  
**Phone**: 402-571-2561

## Technical Details

- Built with **Leaflet.js** for interactive mapping
- Uses **TopoJSON** for efficient county boundary data
- Optimized for print with CSS media queries
- No server required - runs entirely in the browser
- Data loaded from CDN sources for reliability

## Troubleshooting

**Map not loading counties?**
- Check your internet connection (county data loads from external sources)
- Try refreshing the page
- Ensure JavaScript is enabled in your browser

**Print layout issues?**
- Use landscape orientation for best results
- Adjust zoom level before printing
- Try "Print to PDF" for digital archiving

## Updates

To update the jurisdiction data:
1. Edit the `jurisdictions` object in the `<script>` section
2. Update county lists as needed
3. Save and re-upload to GitHub Pages

## License

This map is created for the Mid-America Carpenters Regional Council and affiliated locals.

## Support

For questions about jurisdictions or agreements, contact the local office at 402-571-2561.
