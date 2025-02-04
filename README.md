# 3D Model Viewer

This project is a simple web-based 3D model viewer that utilizes the `<model-viewer>` Web Component to render and display a 3D model.

# This explanation Made by Taha 

## Features
- Loads a 3D model (`cartoon_car.glb`)
- Enables auto-rotation and camera controls
- Uses the `<model-viewer>` component for easy 3D rendering

## Technologies Used
- **HTML5**: Structure of the web page
- **CSS3**: Styling (in `style.css`)
- **JavaScript**: Additional functionalities (in `script.js`)
- **Model Viewer API**: Google’s Web Component for rendering 3D models

## File Structure
```
/project-folder
│── index.html      # Main HTML file
│── style.css       # Styling for the project
│── script.js       # JavaScript logic
│── cartoon_car.glb # 3D model file
```

## How It Works
1. The `index.html` file loads the `<model-viewer>` component from Google's CDN.
2. The 3D model (`cartoon_car.glb`) is displayed with features like:
   - Auto-rotation
   - Camera controls for zoom and movement
3. The `style.css` file can be used to customize the appearance.
4. The `script.js` file can be used to add interactive functionalities.

## Setup & Usage
### Prerequisites
- A modern web browser (Chrome, Edge, Firefox, or Safari)

### Steps to Run
1. Download or clone the repository.
2. Ensure all files are in the same directory.
3. Open `index.html` in a web browser.

### Live Preview
If you want to test it online, you can host it using:
- Local server (e.g., VS Code Live Server extension)
- GitHub Pages
- Netlify or Vercel

## Customization
- Change the `src` attribute of `<model-viewer>` to use a different `.glb` file.
- Modify `style.css` to change appearance.
- Add more JavaScript features in `script.js`.

## Resources
- [Model Viewer Documentation](https://modelviewer.dev/)
- [GLB File Format](https://www.khronos.org/gltf/)