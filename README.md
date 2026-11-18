# Stratis GPS

KiCad schematic and PCB project for the Stratis GPS board.

## Open the project

Open `SidKarynStratisGPS.kicad_pro` in KiCad. The schematic and PCB files should remain beside the project file in the same folder.

## Project files

- `SidKarynStratisGPS.kicad_pro` — KiCad project settings
- `SidKarynStratisGPS.kicad_sch` — schematic
- `SidKarynStratisGPS.kicad_pcb` — PCB layout

## Status

Work in progress. The latest schematic ERC screenshot showed 0 active errors and 0 warnings, with 3 excluded findings and 2 ignored tests. PCB DRC results and physical testing have not been documented here.

## Notes for contributors

- Keep the schematic, PCB, and project files together.
- Do not commit the per-user KiCad project preferences file (`*.kicad_prl`).
- If the project uses custom symbols or footprints, include those libraries and configure project-relative library paths so other contributors can open the design.
