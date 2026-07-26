3D Solar System Simulation
==========================

Overview
--------
This project is an interactive 3D visualization of the solar system built using HTML, CSS, and Three.js. It provides a realistic representation of the Sun and eight planets orbiting around it with accurate relative sizes and orbital speeds.

Features
--------
- Realistic 3D rendering of the solar system with the Sun and all eight planets (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune)
- Orbital mechanics with planet-specific speeds and distances
- Interactive control panel with the following features:
  - Pause/Resume animation
  - Light/Dark mode toggle
  - Reset button to restore default settings
  - Global speed control slider
  - Individual speed control for each planet
- Planet hover information display showing planet name, current speed, and distance
- Click-to-zoom camera functionality
- Responsive design that works on different screen sizes
- Starfield background for immersive experience
- Orbit visualization rings for each planet

Technology Stack
---------------
- HTML5 Canvas
- CSS3 for styling and responsive design
- Three.js (r128) for 3D graphics rendering
- Vanilla JavaScript for application logic

Controls
--------
- Pause Button: Stops and resumes the orbital animation
- Theme Button: Toggles between light and dark background modes
- Reset Button: Resets all speed controls to default values
- Global Speed Slider: Adjusts the overall simulation speed (0x to 5x)
- Planet Speed Sliders: Individual control for each planet's orbital speed
- Mouse Hover: Displays planet information
- Mouse Click: Zooms the camera closer to the scene

Planet Data
-----------
The simulation includes realistic relative properties for each planet:
- Mercury: Smallest planet, closest to the Sun, fastest orbit
- Venus: Second planet from the Sun
- Earth: Third planet with blue coloring
- Mars: Red planet, fourth from the Sun
- Jupiter: Largest planet, fifth from the Sun
- Saturn: Sixth planet with distinctive ring (visualized in color)
- Uranus: Seventh planet with cyan coloring
- Neptune: Eighth and farthest planet

Browser Compatibility
--------------------
This application works best in modern browsers that support WebGL and ES6 JavaScript:
- Chrome (recommended)
- Firefox
- Safari
- Edge

Deployment
----------
This is a static website that can be deployed to any static hosting service such as:
- Netlify
- GitHub Pages
- Vercel
- Any web server

No build process is required. Simply host the HTML file and its dependencies.

File Structure
-------------
- solar system.html - Main application file containing HTML, CSS, and JavaScript
- netlify.toml - Netlify deployment configuration
- README.txt.txt - Project documentation (this file)

Usage
-----
1. Open solar system.html in a modern web browser
2. Use the control panel on the right side to adjust settings
3. Hover over planets to see their information
4. Click anywhere to zoom the camera
5. Adjust individual planet speeds or use the global speed control

License
-------
This project is open source and available for educational and personal use.