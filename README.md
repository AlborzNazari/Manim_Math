# Advanced Manim Animations Collection

[![Manim](https://img.shields.io/badge/Manim-v0.18.0-%23FFD700)](https://www.manim.community/)
[![Python](https://img.shields.io/badge/Python-3.10+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of sophisticated mathematical animations created with Manim:
1. **Torus Knot Visualization**
2. **3D Helix with Tangent Vector**
3. **Parametric Helical Surface**

![Animation Showcase](assets/showcase.gif)

## Features

### 1. Torus Knot Animation
- (p,q) parametric knot visualization
- Dynamic dot tracer with ValueTracker
- Ambient camera rotation
- Configurable torus parameters
- Real-time knot tracing

### 2. Helix with Tangent Vector
- 3D helical motion visualization
- Real-time tangent vector calculation
- Unit vector normalization
- Camera motion synchronization
- Parametric equation display

### 3. Helical Surface Visualization
- Parametric surface rendering (z = y·cos(x))
- Checkerboard pattern surface
- Fixed-frame equation display
- Optimized mesh resolution
- Camera rotation controls

## Installation

```bash
# Clone repository
git clone https://github.com/yourusername/manim-animations.git
cd manim-animations

# Install requirements
pip install -r requirements.txt

# Install Manim dependencies
sudo apt update && sudo apt install ffmpeg
