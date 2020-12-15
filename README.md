Prusa MK3/S to MK3S+
====

### Introduction:

This repository holds the necessary STL and GCodes to print the upgrade parts to turn a Prusa MK3/S into an MK3S+

None of these STL files are my creation, full credit goes to Prusa.

### Printing:

See the [HowToPrintParts_MK3S+.pdf](./HowToPrintParts_MK3S+.pdf) file for instructions on printing.

### Files:

I've included the original [STL files from Prusa](https://www.prusa3d.com/prusa-i3-printable-parts/), gcode files as
well as the PrusaSlicer projects (built in version 2.3.0-beta2+).

All exported gcode files are for a Prusa MK3/S and are all set to print objects individually (part 1 prints completely,
then part 2, etc).

Included are the fan shroud files, but with Prusament ASA settings, although this comes with the 
[upgrade kit](https://shop.prusa3d.com/en/original-prusa-i3-mk3s/1390-original-prusa-i3-mk3-to-mk3s-upgrade-kit.html) if
you purchase that.

### Version:

The STL files included in this repository are from the v1.0.0 release, you should check to ensure you're printing the
latest version here: [https://www.prusa3d.com/prusa-i3-printable-parts/](https://www.prusa3d.com/prusa-i3-printable-parts/)

### Filament:

All filament settings are [Prusament](https://shop.prusa3d.com/en/42-prusament).
 * E-Axis -> PETG (Black)
 * Fan-Shroud -> ASA (Black) (you don't need to print this, it comes with the upgrade kit)
 * LCD-Knob -> PETG (Orange)
 * X-Axis -> PETG (Orange)
 * Y-Axis -> PETG (Black)

### Do I need to print these?

Yes. Yes you do! The upgrade kit from Prusa comes with the items below, but if you want to hit the ground running, you
should print the parts before your kit arrives.
 * [SuperPINDA](https://shop.prusa3d.com/en/spare-parts/1396-superpinda.html)
 * Bearing Clips for Y-axis bearings
 * IR filament sensor + cable
 * Hotend PTFE Tube
 * Fan shroud printed of ASA
 * PETG Filament to print the plastic parts
 
You can find the right filament here: [https://shop.prusa3d.com/en/42-prusament](https://shop.prusa3d.com/en/42-prusament)

### Original Prusa readme...

```text
Original Prusa i3 MK3/MK3S to MK3S+ upgrade
-------------------------------------------

Below is a list of parts needed for the upgrade, choose your current printer and then the one you are upgrading to. Note that some parts are included in the upgrade package as it is difficult to print them yourself.

We recommend using black filament to print all MK3S+ extruder parts. If you want different colour, you can use it, but the FS-lever part should be definitely dark (black) and the other parts surrounding the IR-Sensor as well. In case you use any lighter colour for the FS-lever it might not trigger the sensor.

All the packages are available for download at: https://www.prusa3d.com/prusa-i3-printable-parts/

Changelog
---
v1.0.0 - initial release


MK3S to MK3S+ upgrade
---------------------
Y-axis:
y-rod-holder.stl
LCD-knob.stl

E-axis:
adapter-printer.stl
extruder-body.stl
extruder-cover.stl
extruder-idler.stl
extruder-motor-plate.stl
fan-shroud.stl (included, printed from ASA)
fs-cover.stl
fs-lever.stl
print-fan-support.stl

X-axis (optional):
x-end-idler.stl
x-end-motor.stl
```
