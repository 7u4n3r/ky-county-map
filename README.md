# Kentucky County Interactive Map

ABLE-KY-aligned Kentucky county navigation map.

This repository contains a standalone interactive Kentucky county map designed for county-level resource navigation, civic access, rights-restoration pathways, and public-facing regional orientation.

It was originally built for ABLE-KY resource routing.

## Project role

This repo may contain:

- Kentucky county map interface files
- County-level resource navigation links
- ABLE-KY-facing civic/legal-access routing
- Static HTML/CSS/JS map code
- Accessibility and mobile usability improvements
- Documentation for embedding or adapting the map

## Features

- Clickable Kentucky county regions / markers
- Hover effects showing county names
- Mobile responsive design
- Standalone HTML file
- No dependency-heavy app stack required

## Usage

1. Open `index.html` in any web browser.
2. Click on an active county marker or region.
3. Route the click target to the appropriate county-specific resource page.

## Customization

Edit the county click handler in `index.html` to change where county clicks redirect.

Example:

```javascript
function handleCountyClick(county) {
    const url = `https://able-ky.org/county/${county.toLowerCase()}`;
    window.location.href = url;
}
```

## Files

- `index.html` - main interactive map file
- `kentucky-map.png` - Kentucky counties map image
- `README.md` - project overview
- `PROJECT_BOUNDARY.md` - project containment rules

## Integration

To embed this map in another site:

```html
<iframe src="path/to/index.html" width="100%" height="800px" frameborder="0"></iframe>
```

Or copy the HTML/CSS/JS directly into an existing page.

## What belongs elsewhere

| Material | Belongs in |
|---|---|
| Perspection governance, refusal rules, copy lint, audits | `7u4n3r/Perspection` |
| Faceless Reclaimation public-facing story/reclaiming material | `7u4n3r/faceless-reclaimation` |
| Trinity-specific framework/site material | `7u4n3r/trinity-framework-site` |
| Working tool experiments, Manus build fragments, UI drafts | `7u4n3r/Trinity-tools` |
| Neutral system analysis and evidence mapping | `7u4n3r/system-analysis-reference` |

## Boundary rule

This repository is a navigation tool.

It helps people find the right county-level direction.
It does not absorb the full ecosystem.
It does not become governance, testimony, or analysis by default.

## License / attribution

Built for ABLE-KY-aligned resource navigation using Trinity Framework™ structure.
