# Kentucky County Interactive Map

Interactive map of Kentucky counties with clickable regions for ABLE-KY resource navigation.

## Features

- 60+ clickable blue counties where ABLE-KY is active
- Hover effects showing county names
- Mobile responsive design
- Standalone HTML file - no dependencies

## Usage

1. Open `index.html` in any web browser
2. Click on any blue county dot to navigate to that county's page
3. Hover over dots to see county names

## Customization

Edit the `handleCountyClick` function in `index.html` (line 186) to change where county clicks redirect:

```javascript
function handleCountyClick(county) {
    const url = `https://able-ky.org/county/${county.toLowerCase()}`;
    window.location.href = url;
}
```

## Files

- `index.html` - Main interactive map file
- `kentucky-map.png` - Kentucky counties map image
- `README.md` - This file

## Integration

To embed this map in your website:

```html
<iframe src="path/to/index.html" width="100%" height="800px" frameborder="0"></iframe>
```

Or copy the HTML/CSS/JS directly into your existing page.

## License

Built for ABLE-KY using Trinity Framework™
