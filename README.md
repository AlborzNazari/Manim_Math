# Advanced Manim Animations Collection

[![Manim](https://img.shields.io/badge/Manim-v0.18.0-%23FFD700)](https://www.manim.community/)
[![Python](https://img.shields.io/badge/Python-3.10+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository showcases a collection of mathematical animations crafted with [Manim](https://www.manim.community/), a Python library for precise and dynamic visualizations. These animations transform complex mathematical concepts into elegant shapes and motions, highlighting the inherent beauty and dynamism of mathematics with clarity and precision.

![Animation Showcase](assets/showcase.gif)

## Animations

- **Torus Knot Visualization**
  - Renders a (p, q) parametric knot on a torus
  - Uses `ValueTracker` for a dynamic dot tracer
  - Features ambient camera rotation
  - Includes configurable torus parameters
  - Traces the knot in real time

- **3D Helix with Tangent Vector**
  - Visualizes 3D helical motion
  - Calculates tangent vectors in real time
  - Normalizes unit vectors
  - Synchronizes camera motion
  - Displays parametric equations

- **Parametric Helical Surface**
  - Renders a parametric surface defined by \( z = y \cdot \cos(x) \)
  - Applies a checkerboard pattern
  - Shows a fixed-frame equation
  - Uses optimized mesh resolution
  - Includes controlled camera rotation

- **Circle Elements Step-by-Step**
  - Sequentially constructs a circle’s elements: circle, radius, diameter, secant, tangent, and chord
  - Uses `Tex` objects for dynamic labeling
  - Employs `Create`, `Write`, and `FadeOut` for smooth transitions
  - Presents a clear progression of geometric concepts

- **Parallelepiped Animation**
  - Visualizes a 3D parallelepiped with vertex manipulation and scaling
  - Features gradient coloring based on z-coordinate interpolation
  - Integrates `ThreeDAxes` for spatial context
  - Uses ambient camera rotation for full viewing angles
  - Groups faces in a `VGroup` for streamlined animations

- **Rhombicuboctahedron 3D**
  - Constructs a rhombicuboctahedron with defined vertices and faces
  - Combines triangular and square faces with custom shading and opacity
  - Creates manual edges to highlight structure without duplication
  - Enhances 3D perception with ambient camera rotation
  - Animates creation for clarity

- **Terrain Animation**
  - Renders a 3D terrain using a height function with multiple Gaussian peaks
  - Maps z-values to blue-to-green color interpolation
  - Defines surfaces with adjustable resolution
  - Integrates `ThreeDAxes` for spatial reference
  - Features dynamic ambient camera rotation

- **Trapezoid with Formula**
  - Builds a trapezoid with bases, legs, and a dashed height line
  - Labels geometric dimensions
  - Demonstrates the area formula in real time
  - Organizes animations for a sequential presentation
  - Concludes with a comprehensive fade-out

## Installation

To run these animations locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/manim-animations.git
cd manim-animations

# Install Python dependencies
pip install -r requirements.txt

# Install system dependencies (Ubuntu/Debian)
sudo apt update && sudo apt install ffmpeg

