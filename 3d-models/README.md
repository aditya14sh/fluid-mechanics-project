# 3D models – curved gate physical model

STL files for 3D printing the model (rig version v14). Click any `.stl` file on GitHub to rotate it in 3D in the browser. The number after `_x` in a file name is how many to print.

| File | Part | Size (mm) |
|---|---|---|
| `SidePlate_A_x1.stl`, `SidePlate_B_x1.stl` | Side plates with the curved gate profile and the 5 pulley axle posts | 271 × 151 × 40.5 |
| `Floor_LeftWall_x1.stl` | Floor and left wall of the container | 50.9 × 106 × 80 |
| `Gate_x1.stl` | Quarter-circle gate, R = 100 mm, hinged at the bottom | 107.5 × 104.5 × 79.4 |
| `Pulley_P1_x1.stl` … `Pulley_P5_x1.stl` | Pulleys P1–P5 for the F<sub>H</sub> and F<sub>V</sub> threads | Ø20 × 6 |
| `Counterweight_Fh_400g_x1.stl`, `Counterweight_Fv_628g_x1.stl` | Counterweight cups for the F<sub>H</sub> (400 g) and F<sub>V</sub> (628 g) threads | 30 × 70 × 60, 36 × 70 × 80 |

## Printing
PLA or PETG, 0.2 mm layers, 4 walls, 30 %+ infill. See [`PRINT_LIST.txt`](PRINT_LIST.txt) for print orientation.

- Side plates: outer face down, axle posts pointing up, no supports.
- Floor/left wall and gate: lay flat on a side face, no supports.
- Pulleys: flat, no supports. Counterweight cups: upright.

## Hardware (not printed)
- 6 × 4 mm diameter rods (5 pulley axles + hinge), with washers.
- Thread for the F<sub>H</sub> and F<sub>V</sub> lines, and small hooks.
- Silicone bead to seal the joints.

Note: the gate is printed 79.4 mm wide to leave a 0.3 mm gap on each side between the 80 mm side plates, so it can swing freely. Section 7.1 of the report works out the effect on the forces (0.75 %).
