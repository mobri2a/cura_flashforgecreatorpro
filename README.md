# Flashforge Creator Pro Cura Settings

These setting are tested with:

* Ultimaker Cura 4.4.1
* Raspberry Pi 3B+
* OctoPrint 1.3.12
* GPX Plugin 2.6.3
* PSU Control 0.1.9 (not yet working)

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
* [Makerbot gcode](http://makerbot.wikidot.com/gcode)
* [RepRap gcode](https://reprap.org/wiki/G-code)
* [OctoPrint Mod for Flashforge Creator Pro](https://www.instructables.com/id/OctoPrint-Mod-for-FlashForge-Creator-Pro/)
* [Flashforge Creator Pro & Raspberry Pi 2 & Octoprint](https://www.thingiverse.com/groups/flashforge/forums/general/topic:11749)
* [Thingiverse Flashforge Thread](https://www.thingiverse.com/groups/flashforge/forums/general/topic:11749)
* [Flashforge group](https://groups.google.com/forum/#!forum/flashforge)
* [Octoprint group](https://groups.google.com/forum/#!forum/octoprint)
* [GPX group](https://groups.google.com/forum/#!forum/gpx-converter)
* [Slic3r manual](http://manual.slic3r.org/)
* [Alternative Pi case](https://www.thingiverse.com/thing:947903)

## To Do

* Verify GPIO pin and voltage of the relay.
* Review everything and document what worked (and what did not), what was worth doing (and what was not).