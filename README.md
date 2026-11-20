# Fluid Mechanics Project – Curved Gate

Interactive website for our Fluid Mechanics project: hydrostatic forces on a quarter-circle gate hinged at the bottom, with the pulley and counterweight rig of our physical model.

**Live site:** https://aditya14sh.github.io/fluid-mechanics-project/

## What it does
- Calculates the horizontal force F_H, vertical force F_V and resultant F_R on the gate
- Animated cross-section: water filling and draining, gate swinging about the hinge, pulleys and counterweight cups moving
- Units in m, cm or mm and N or kN; change radius, width, base length, water depth, liquid density, gate mass and counterweights
- Presets: ideal model (weightless gate), real model (35 g gate), model with no cups, half full, and the course cases R = 0.5 to 1.5 m
- Theory section with the equations and the numbers for the current setup

Open a preset directly by adding a tag to the link, e.g. `#model-ideal`, `#model-real`, `#r100`.

## Project report
The full project report is in [`report/Fluid_Mechanics_Project_Report_Curved_Gate.docx`](report/Fluid_Mechanics_Project_Report_Curved_Gate.docx) (on that page, click **View raw** to download it and open it in Word).

## 3D models
The STL files for 3D printing the physical model are in [`3d-models/`](3d-models/), with a parts list and print settings. GitHub shows each `.stl` file as a 3D view you can rotate in the browser.

## Files
- `index.html` – the whole website (HTML, CSS and JavaScript in one file, no build step)
- `report/` – the project report (Word)
- `3d-models/` – STL files of the physical model for 3D printing

Aditya Sharma, CE25B001
