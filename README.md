# Vynte Puck

KiCad hardware design for the Vynte room-temperature puck, part of a room-by-room HVAC comfort system.

## Open the project

Open `Puck.kicad_pro` in KiCad. The main schematic and PCB are `Puck.kicad_sch` and `Puck.kicad_pcb`. Supporting sheets cover the temperature sensor, seven-segment display, voltage regulator, USB Type-C receptacle, and external programming interface. Custom symbols, footprints, models, and a sensor datasheet are included in `Comps/`. Library tables are included at the project root.

## Saved fabrication files

`production/` contains the existing `Puck_0.5.0.zip` fabrication archive, BOM/designator/placement CSV exports, IPC netlist, and stencil layers. `fabrication-toolkit-options.json` preserves the export settings. These files are archived exports, not a verified manufacturing release. Regenerate fabrication files from the intended design and review DRC/ERC before ordering boards.

## Synchronization status

This snapshot preserves the saved local design as of October 26, 2026. Its source branch started at `d32a3a6`, while Gitea main had advanced by 14 commits to `c4a697f`. Combining the branches produces conflicts in `Puck.kicad_pcb`, `Puck.kicad_sch`, and `Puck.kicad_pro`. The saved design is submitted as a pull request for review; it has not been reconciled with or merged into main.

The public GitHub copy starts with a clean snapshot and excludes earlier development history. Gitea remains the development repository. Local backups, analysis caches, and per-user KiCad settings are excluded.

No open-source license has been selected.
