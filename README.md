<p align="center">
  <img src="https://github.com/mkturkcan/Shadowcast/blob/main/assets/logo.png?raw=true"  width="256" />
</p>

# Shadowcast

A real-time 3D visualization of building footprints with dynamic shadow studies. Built with Three.js and OpenStreetMap data. Supports any city.

<p align="center">
  <img src="https://github.com/mkturkcan/Shadowcast/blob/main/assets/example.png?raw=true" />
</p>

## Features
- Real-time shadow casting with adjustable light position
- Orthographic and perspective camera modes
- Material Design UI with dark theme
- Physically-based rendering with metallic materials
- Building heights from actual OpenStreetMap data
- Soft shadows with adjustable parameters
- Responsive design that scales to any viewport

## Setup
1. Clone the repository
2. Serve with any HTTP server (e.g., `python -m http.server` or `npx serve`)
3. Open in a browser that supports ES modules
4. Use polygonhelper.html to edit the area to be used for the renders

## Dependencies
- Three.js 0.153.0
- Materialize CSS 1.0.0
- No build process required

## Data
Building footprints and heights are fetched dynamically from OpenStreetMap via Overpass API, centered on Manhattan.

## License
MIT