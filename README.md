# Flashforge Creator Pro Cura Settings

These setting are tested with Ultimaker Cura 4.4.1.

## Installation

1. Copy the files in **definitions**, **extruders**, **images**, and **meshes** to the corresponding folder under your *Ultimaker Cura 4.x* **resources** folder.

2. Start Cura

3. Add a Printer

4. Select *Flashforge* -> *Flashforge Creator Pro*

## Notes

### gcode vs x3g

Cura can slice to x3g using the X3GWrite plugin. That's great for printing from an SD card, but not so much for using OctoPrint. OctoPrint is unable to send the binary x3g code to the printer. When slicing for OctoPrint output is **gcode**. When slicing for SD card output is **x3g**.

### machine_center_is_zero

Should be TRUE. Make sure that the OctoPrint printer profile has the origin set to center, as well.

## References
(Makerbot gcode)[http://makerbot.wikidot.com/gcode]
