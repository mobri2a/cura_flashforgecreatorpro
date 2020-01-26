# Change Log

## [0.1.1] - 2020-01-26

### Changed
- Removed extruder gcode. It seems to add nothing.
- Removed T0 in printer start gcode - sets right as active extruder (right worked fine; left did not)

### Results
- Slow head movement issue solved.
- Extrudes on correct extruder
- Cancel behavior from the printer - stops as expected, but Pi still sending gcode. Had to power off/on.

## [0.1.0] - 2020-01-26

### Added
- Values based on a couple of the internet sites
- Testing for bed position and extrusion

### Results
- Extruder (left) extruded virtually nothing.
- Moves head too fast during homing
- Cancel from OctoPi does not work
