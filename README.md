# THERMO — Interactive Thermodynamics Studio

A redesigned front end and companion toolkit for the original **Heat Transfer Lab**. The original simulator is preserved as `lab.html`; the new landing page, 3D explorer, and engineering calculators are added around it.

## Included
- `index.html` — responsive dashboard / project home.
- `lab.html` — original Heat Transfer Lab, preserved from the uploaded project.
- `models.html` — interactive Three.js models: piston-cylinder, molecular chamber, and conceptual heat-transfer model.
- `calculators.html` — sensible heat, ideal gas law, First Law energy balance, and linear thermal expansion.
- `app.css`, `app.js` — shared dashboard styling and 3D hero scene.
- `LICENSE` — original MIT license, retained from the source project.

## Run locally
Extract the ZIP and open `index.html` in a modern browser. For best results, serve the folder through a local static server. No backend is required.

## GitHub Pages
Upload the contents of this folder to the repository root (or a folder configured for Pages). Set the Pages source to the desired branch and directory. Relative links are used between pages.

## Notes
- Three.js and Google Fonts are loaded from CDNs, so an internet connection is needed for those resources.
- The original lab's simulation logic and interface are preserved in `lab.html`.
- The new 3D models are conceptual educational visualizations, not precision CAD or molecular-dynamics simulations.
- Calculator outputs follow idealized textbook equations. Verify units and assumptions before using values in real engineering work.
- The original project was distributed under the MIT License. That license file is retained; review it before relicensing or redistributing the combined project.

## Original project
The original upload identified the project as **Heat Transfer Lab** and credited `frinzangelo0714-hue` in its MIT license.
