# High-Fidelity 3D Interactive Earth Globe

An advanced, interactive 3D Earth Globe built with Three.js, OrbitControls, and custom GLSL Shaders for realistic planetary rendering.

![Realistic Earth Globe](https://unpkg.com/three-globe/example/img/earth-blue-marble.jpg)

## Features
- **Dynamic Day/Night Blending**: Custom GLSL shader that blends day (satellite) and night (city lights) textures in real-time according to sun light direction.
- **Volumetric Atmospheric Scattering**: Custom Fresnel glow shader simulating atmospheric scattering around the Earth's rim.
- **Interactive Orbit Controls**: Smooth rotations with damping, zoom boundaries, and pan support.
- **Adjustable Controls**:
  - Rotation Speed
  - Sun Position (simulate different times of day)
  - Cloud Density
  - Atmosphere Glow Intensity
- **Fallback Support**: Generates procedural canvas textures automatically if CDN network assets fail to load.

## Setup & Running Locally
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd "3 D model globe"
   ```
2. Run a local web server (e.g., using Python or http-server):
   ```bash
   npx http-server -p 8080
   ```
   Or:
   ```bash
   python3 -m http.server 8080
   ```
3. Open `http://localhost:8080/3D model.HTML` in your web browser.

## Built With
- [Three.js](https://threejs.org/) - 3D library
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) - Interactive camera controls
- Custom WebGL Shaders (GLSL)
