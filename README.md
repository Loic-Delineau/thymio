# thymio
MICRO-452 Basics of Mobile Robotics &amp; Thymio Robot

## Gantry
You will find all information regarding the gantry in the 
![gantry/](./gantry) directory.

The gantry is the large jig designed to slide right over a workbench 
tabletop like the ones you find in the DLLELL Atrium Room (The SPOT). 

The stock needed to build a gantry is:

- 3x 800x930mm 3mm MDF

You can find this exact stock already cut to those exact dimensions 
inside the mechanical lab of DLL, say hi to Ivan for me ;)

This stock will cost you a total of:

- 16.38CHF (7.34CHF/m2)

The MDF is designed with box joints such that it perfecty assembles and 
disassembles for storage in a very tight 9mm thick slot as to save space
when not in use.

The gantry also includes holes for routing the Aukey 1080P Webcam 
USB cable and its ferrite choke as provided 
for the MICRO-452 EPFL class. 

To get the same results after all the machine tolerances,
it is recommended to use the:

- lightburn file (.lbrn2)        --> 150W CO2 Laser from DLLEL
- binary gcode file (.bgcode)	 --> Prusa MK4 from DLL

On the DLL Laser cutter with a 150W CO2 Tube, this give the following settings:
- 350mm/s @ 35% power for the engraving
- 25mm/s @ 80% power for the cutting

Finally a 3D printed part holds the camera and slots inside of the
crossbeam, it is also provided in the ![gantry/](./gantry) directory. 



