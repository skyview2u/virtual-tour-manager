# Virtual Tour Manager

A comprehensive 360° virtual tour management system built with React and Three.js.

## Features

- 360° panoramic scene viewer
- Hotspot management (navigation, info points, media links)
- Scene carousel navigation
- Mapbox integration with 3D maps
- Top HUD navigation system
- Camera inertia for smooth viewing
- Drag-and-drop scene reordering
- Custom hotspot icons
- localStorage persistence

## Deployment

### Netlify (Recommended)

1. Fork this repository
2. Go to [Netlify](https://app.netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Choose GitHub and select this repository
5. Deploy! (No build settings needed - it's a static site)

### Manual Deployment

Simply upload the `index.html` file to any static hosting service.

## Usage

1. **Create a Tour**: Add a new tour from the dashboard
2. **Add Scenes**: Upload 360° images for each scene
3. **Add Hotspots**: Place navigation points and info hotspots
4. **Set Locations**: Use the Map feature to set GPS coordinates
5. **Preview**: View your tour in action
6. **Share**: Share the URL with viewers

## Configuration

### Mapbox Token

The app includes a default Mapbox token. For production use, replace it with your own:

1. Get a free token at [Mapbox.com](https://account.mapbox.com/)
2. In `index.html`, find: `const MAPBOX_TOKEN = 'your-token-here'`
3. Replace with your token

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Technical Stack

- React 18
- Three.js
- Mapbox GL JS
- Tailwind CSS
- localStorage for data persistence

## License

MIT License - feel free to use and modify!

## Credits

Created with Claude AI
