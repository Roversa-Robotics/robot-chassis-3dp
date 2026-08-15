# robot-chassis-3dp

A 3D-printable (3DP) chassis for the Roversa robot, designed in Fusion 360.

Credit to the Paola Harris Bonet at Universidad del Norte for the initial design that I've built upon.

The design uses common parts also used in the Laser Cut (LC) version of the chassis--the buttons, wheels, and ball bearing holder (but not the battery holder from the LC version). The Roversa PCB board, servos, battery and Micro:Bit complete the assembly.

## Repository contents

```
charging-station-3dp/
├── LICENSE
├── README.md
├── cad/              Source Fusion 360 (.f3d) archive
└── exports/
    ├── stl/          Generated STL files, ready to slice/print
    └── step/         Generated STEP files, for use in other CAD tools
```

- **`cad/`** — Archived versions of the Fusion 360 source file. Since `.f3d`
  is a binary format, version history here is file-based rather than
  diff-based — see [Versioning](#versioning) below.
- **`exports/stl/`** and **`exports/step/`** — Generated output files. These need to 
  be regenerated any time the `cad/` version is updated and should be committed in the
  same pull request with the `.f3d` update. 
  
Although this design includes buttons and wheels for a complete assembly, they are maintained in the LC Chassis design in OnShape. Only the following STL files come from this design:
- roversa-motor-tension-block.stl (from the SERVO TENSOR body)
- roversa-microbit-cover.stl (from the MICROBIT body)
- roversa-front.stl (from the PUERTA body)
- roversa-buttons-cover.stl (from the BOTONES body)
- roversa-body.stl (from the CUERPO 1 body)
- roversa-battery-cover.stl (from the TAPA BATERIA body)

## Software

- **Fusion 360** — primary CAD tool used for design.

## Printing notes

The parts have been printed using PETG with a Bambu X1C with `0.16mm Optimal @BBL X1C` settings on the Textured PEI plate. The main body requires enabling supports (though I'm hoping to eliminate that need in a future version).

## License

This project is licensed under the [MIT License](LICENSE).
