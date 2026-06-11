# Interactive Mohr's Circle

Educational interactive web app for visualizing Mohr's circle and plane stress transformations.

Live demo: https://angelosimone.github.io/interactive-mohrs-circle/

## Overview

This app allows users to explore the relationship between a plane stress tensor, its rotated components, principal stresses, and the corresponding Mohr's circle representation.

The visualization includes:

- Mohr's circle in the σ<sub>n</sub>-τ<sub>n</sub> plane
- the physical stress element
- the rotated stress tensor
- principal stresses
- shear stress transformation
- physical rotation angle

## Sign convention

The app follows the Mohr's circle sign convention in which:

- positive normal stress corresponds to tensile stress;
- positive shear stress in the Mohr plane corresponds to clockwise rotation of the material element;
- the physical stress tensor is represented using the standard tensor convention.

See the [Wikipedia article on Mohr's circle](https://en.wikipedia.org/wiki/Mohr%27s_circle) for details. This app follows sign convention #3 in Figure 5, as described in the article version accessed on June 11, 2026.

## Usage

Open the [live web app](https://angelosimone.github.io/interactive-mohrs-circle/) or download `index.html` and open it locally in a browser.

Enter the stress components:

- σ<sub>xx</sub>
- σ<sub>yy</sub>
- τ<sub>xy</sub>

Then click **Apply**.

You can drag the red or green marker on Mohr's circle to rotate the stress element and inspect the transformed stress state.

The app is fully client-side and can be used offline.

## Repository contents

- `index.html`: standalone HTML/CSS/JavaScript web app
- `README.md`: project documentation
- `LICENSE`: MIT License

## License

Copyright (c) 2026 Angelo Simone.

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Angelo Simone  
Università di Padova
