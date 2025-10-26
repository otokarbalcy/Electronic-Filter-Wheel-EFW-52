# Electronic-Filter-Wheel-EFW-52
3D-printable Astrophotography Electronic Filter Wheel EWF-52 (2" filters x5)

The firmware is based on https://github.com/chemistorge/Arduino-Motorised-Filter-Wheel-Xagyl-compatible-ASCOM-and-INDI-

The electronics part of the wheel is based on ESP32-C3 MCU and the custom board I designed. A small OLED display shows the number of the currently selected filter. 
A cheap 28BYJ-48 stepper motor motorises the wheel. 

**3D Print**

- All of the parts have been printed with BambuLab ABS, except for the optional gasket printed with TPU.
- Take material shrinkage into account. For BambuLab ABS, enlarging the parts to 101% works fine. It also provides a good tolerance for precise M42 threads.
- All of the parts have been printed with 0.2 mm layer height, except for the parts with M42 threads: The Main Gear and The Back Housing Insert. These were sliced with 0.08 mm layer height.
- 3D printing strenght settings: 8x outline, 5x bottom/top layers, 25% infill. 
