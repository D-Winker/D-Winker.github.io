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
    image_path: "assets/projects/ExampleSudoku_Solver1.png"
    title: "Sudoku Solver"
    excerpt: "I wrote six different Sudoku solvers. Four of them work!"
    image_caption: "[**Example Sudoku, initialized for solving**](https://github.com/D-Winker/SudokuSolver)"
  - url: "https://github.com/D-Winker/Pybadge_Thermal_Depth_Camera"
    image_path: "assets/projects/ThermalVisualization-2.png"
    title: "Thermal & Depth Camera"
    excerpt: "I augmented Adafruit's 32x24 thermal camera project with an 8x8 depth sensor, and added a few features to the code - CSV recording, 2x and 4x interpolation, moving averaging, and more."
    image_caption: "[**A 3D thermal picture of myself**](https://github.com/D-Winker/Pybadge_Thermal_Depth_Camera)" 
  - url: "https://github.com/D-Winker/OpenSCAD_Designs/tree/main"
    image_path: "assets/projects/slash_a-arm.png"
    title: "OpenSCAD Designs"
    excerpt: "OpenSCAD is a script-based 3D design tool. I love it! Here are some things I designed in OpenSCAD."
    image_caption: "[**Replacement Traxxas Slash A-Arm**](https://github.com/D-Winker/OpenSCAD_Designs/tree/main)"
  - url: "https://github.com/D-Winker/TSL2591_AutoAdjust/tree/master"
    image_path: "assets/projects/BrightnessMeasurements.png"
    title: "Lux Meter"
    excerpt: "I added automatic gain control to Adafruit's example code for the TSL2591 light sensor."
    image_caption: "[**24 hours of lux data**](https://github.com/D-Winker/TSL2591_AutoAdjust/tree/master)"
  - url: "https://github.com/D-Winker/Audio-Visual-MSGEQ7-/tree/master"
    image_path: "assets/projects/AudioVisualGif.gif"
    title: "Audio Beat Detection"
    excerpt: "Dual channel beat detection used to control a set of RGB LEDs, combined with a set of speakers, built into an old XBOX360 shell."
    image_caption: "[**The code in action**](https://github.com/D-Winker/Audio-Visual-MSGEQ7-/tree/master)"
  - url: "https://github.com/D-Winker/JoystickMouse"
    image_path: "assets/projects/CompletedJoystickMouse.jpg"
    title: "Joystick Mouse"
    excerpt: "I modified an old serial-interface joystick to be usable as a USB mouse. An Arduino dev board reads the potentiometers and buttons, then relays the programmed commands to the computer: mouse movement, right, left, and middle click, alt+tab, ctrl+tab, and ctrl+shift+tab."
    image_caption: "[**The augmented joystick**](https://github.com/D-Winker/JoystickMouse)"
  - url: "https://github.com/D-Winker/Trace"
    image_path: "assets/projects/TraceDemo.png"
    title: "Trace"
    excerpt: "A multi-dimensional plotter intended for use with real-time, real-world data sources."
    image_caption: "[**A demo plot**](https://github.com/D-Winker/Trace)"
  - url: "https://www.instructables.com/Cardboard-Couch-1/"
    image_path: "assets/projects/CardboardCouch.jpg"
    title: "Cardboard Couch"
    excerpt: "I bought a bed from IKEA and thought it would be funny to make more furniture from the packaging. (Supports up to 3 adults)."
    image_caption: "[**The cardboard couch**](https://www.instructables.com/Cardboard-Couch-1/)"
  - url: "https://www.instructables.com/Fleece-Scarf/"
    image_path: "assets/projects/FleeceScarf.jpg"
    title: "Fleece Scarf"
    excerpt: "A scarf woven from tubes made of fleece."
    image_caption: "[**The scarf**](https://www.instructables.com/Fleece-Scarf/)"
  - url: "https://www.instructables.com/DIY-Oyule-Lamp/"
    image_path: "assets/projects/OyuleLamp.jpg"
    title: "Replica Oil Lamp"
    excerpt: "This is a DIY recreation of the 'Oyule' lamp, created by artist Sergio Silva."
    image_caption: "[****](https://www.instructables.com/DIY-Oyule-Lamp/)"

---

{% include feature_row id="projects_intro" type="center" %}
{% include feature_row id="projects" %}
