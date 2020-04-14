# Mod-Frog
This project is a hobby project to convert an existing 3D printer to a “better” machine. Currently it’s based on the CoreXY principle https://www.corexy.org/theory.html

This project and me are not related  to the company; Leapfrog. I bought the machine at the beginning of 2015 and almost immediately started tinkering with it. 

There we’re multiple iteration on the design but it was never the intent to share these designs. As a consequens the design files are a bit of a mess but still usable. If someone is willing to continue working a version please feel free and share it on this github. 

During the design proces a lot of inspiration came from other CoreXY systems like the Hypercube, S.T.E.V.E. & Voron designs. These and others printers we're great design inspirations!

# Current setup:
Short: 24V Corexy system with direct extruder and a build volume of 280x340x150(XYZ)
Electronics:
- Re-arm (32 bit) https://reprap.org/wiki/Re-ARM
- Ramps 1.4 (24v)
  - TMC2100 for X&Y
  - DRV8825 for Z & E
- Raspberry pi 2b (running Octoprint)
- Nema 17 for X&Y
- Nema 23 for Z (See next steps)

Print head & Bed:
- Bltouch 
- Radial parts cooling fan (50x50)
- Hemera https://e3d-online.com/e3d-hemera-175-kit
- Heavy lead screw ball bearing
- 350 x 450 Silicone heater 220V 1000W with glass plate on top

Motion system:
- Gates GT2 belts
- Cheap chinese pulley's (See next steps)
- 8 mm rods on X (See next steps)
- 10 mm rods on Y

# Next steps
- Experiment with Carbon fiber rods on X 
  - Rods from:https://www.ebay.com/str/haozhongcarbonfibertube
  - IGUS JSM bearings
- Improve rigidity of the frame by replacing top plate with 40x40 extrusion profile 
- Tidy up the electronis
- Convert to Dual Z Nema 17 motors for higher Z speed en less noise
