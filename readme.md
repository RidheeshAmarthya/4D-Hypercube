## 4D Hypercube Visualization

This project provides an interactive visualization of a 4D hypercube (tesseract) using HTML and JavaScript. It allows users to explore the complex geometry of a 4D object projected into 3D space, complete with rotation controls and a 3D shadow representation.

### Features

- Interactive 4D hypercube visualization
- Real-time rotation in all six 4D planes (XY, XZ, XW, YZ, YW, ZW)
- Adjustable scale
- Auto-rotation option
- 3D shadow cube toggle
- Responsive design

### Technologies Used

- HTML5
- JavaScript
- Three.js (for 3D rendering)
- dat.GUI (for user interface controls)

### How to Use

1. Clone this repository or download the HTML file.
2. Open the HTML file in a modern web browser (Chrome, Firefox, Safari, or Edge recommended).
3. Use the GUI controls on the right side of the screen to interact with the visualization:
   - Adjust rotation sliders for each plane
   - Change the scale of the hypercube
   - Toggle auto-rotation on/off
   - Show/hide the 3D shadow cube

### Controls Explanation

- **Rotation Sliders**: Control the rotation of the hypercube in different 4D planes.
- **Scale**: Adjust the size of the hypercube and its shadow.
- **Auto Rotate**: When enabled, the hypercube will rotate automatically.
- **Show Shadow**: Toggle the visibility of the 3D shadow cube.

### Understanding the Visualization

- The white wireframe represents the 4D hypercube projected into 3D space.
- The gray wireframe (when shadow is enabled) shows the 3D shadow of the hypercube.
- As you rotate the hypercube, observe how its shape and its shadow change, providing insights into 4D geometry.

### Customization

You can customize the visualization by modifying the JavaScript code:
- Adjust colors of the hypercube and shadow
- Change the position of the shadow cube
- Modify rotation speeds or add new interactive elements

### Requirements

- A modern web browser with JavaScript enabled
- No additional installation required; the necessary libraries (Three.js and dat.GUI) are loaded via CDN

### License

This project is open source and available under the MIT License.

### Acknowledgements

This visualization is based on concepts from 4D geometry and uses the Three.js library for 3D rendering and dat.GUI for the user interface.
