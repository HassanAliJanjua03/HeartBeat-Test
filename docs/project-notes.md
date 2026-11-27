# Project notes

## Design files

The repository retains the original [Proteus project](../Hearbeat%20Test.pdsprj). Its archive directory includes:

| File inside Proteus archive | Role |
| --- | --- |
| ROOT.DSN | Schematic design |
| ROOT.LYT | PCB layout |
| ROOT.CDB | Proteus project data |
| PROJECT.XML | Project metadata |
| SCRIPTS/PWRRAILS.DAT | Power rail settings file |

Open the project in Proteus to inspect the actual design and component connections. The repository description identifies ATmega328P as its main microcontroller. The schematic's component values, sensor arrangement and firmware have not been independently verified here.

## Physical board

The [original PCB photograph](../PCB.jpg) shows conductive tracks, pads and drilled holes. It documents the bare-board fabrication stage, rather than a fully populated circuit or a measured test result. The [original demonstration recording](../PCB%20Video.mp4) and [report](../Project%20Report.pdf) are retained for further context.

## Review before reproducing

- Inspect the schematic, layout, component pin assignments and power rails in Proteus.
- Confirm component values, footprints, board dimensions and supply requirements from the original project.
- Verify trace continuity and absence of shorts before powering the board.
- Review firmware requirements; separate firmware source is not published here.
- Use appropriate electrical isolation and safety precautions for any human-contact circuit. Do not connect an unverified prototype to a person.

No new circuit simulation, hardware measurement or clinical validation has been performed for this repository update. The original report and video are preserved without changes; the report contents and video playback were not independently reviewed.

[Back to project](../README.md)
