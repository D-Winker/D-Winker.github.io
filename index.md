---
layout: splash
classes: wide
permalink: /
header:
  overlay_filter: linear-gradient(rgba(0, 0, 0, 0.5), rgba(234, 133, 52, 0.5))
  overlay_image: "https://images.unsplash.com/photo-1596213812143-ff89bd9ddecd?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1450&q=80"
  caption: "[**Mika Baumeister**](https://unsplash.com/@mbaumi) on [*Unsplash*](https://unsplash.com)"
projects_intro:
  - title: Projects THIS PAGE IS A WORK IN PROGRESS! I'm modifying the CMU page into my own...
  - excerpt: 'Here are all of my projects, old, new, completed, and ongoing.'
projects:
  - url: "https://github.com/D-Winker/SudokuSolver"
    image_path: "https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Sudoku_Puzzle_by_L2G-20050714_standardized_layout.svg/1200px-Sudoku_Puzzle_by_L2G-20050714_standardized_layout.svg.png"
    title: "Sudoku Solver"
    excerpt: "Two different ways to solve a Sudoku."
    image_caption: "**Example Sudoku from Wikimedia**"
  - url: "https://github.com/D-Winker/Pybadge_Thermal_Depth_Camera"
    image_path: "https://cdn-learn.adafruit.com/guides/cropped_images/000/002/983/medium640/hero-printers-crop.jpg?1587498704"
    title: "Thermal & Depth Camera"
    excerpt: "I augmented Adafruit's 32x24 thermal camera project with an 8x8 depth sensor, and added a few features to the code - CSV recording, 2x and 4x interpolation, moving averaging, and more."
    image_caption: "Image from Adafruit" 
  - url: "https://github.com/D-Winker/OpenSCAD_Designs/tree/main"
    image_path: "assets/projects/slash_a-arm.png"
    title: "OpenSCAD Designs"
    excerpt: "OpenSCAD is a script-based 3D design tool. I love it! Here are some things I designed in OpenSCAD."
    image_caption: "[**Replacement Traxxas Slash A-Arm**](https://github.com/D-Winker/OpenSCAD_Designs/tree/main)" 

---

{% include feature_row id="projects_intro" type="center" %}
{% include feature_row id="projects" %}
