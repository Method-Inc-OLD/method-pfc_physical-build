# Mechanical

## Overview
The chassis is designed around a central 50cm3 acrylic chamber surrounded by a number of modules. All connectors are 3D printed, and all supporting materials are 21mm wood. This design makes it easy to grow or shrink the size of the box for revised designs or differently sized acrylic chambers. We recommend using tough filament. 

The PFC is designed with 4 modules: Bottom, Middle, Top, and Side. Each module has a number of 3D printed connectors. This repository contains 3D Rhino files with individual 3D print blocks, and assemblies for each module as well as one overall assembly.

### Modules
![Full Overview, Front](/Documentation/ModelOverview/mPFC-Model-Overview-Full-FrontView.jpg)
![Back Overview, Front](/Documentation/ModelOverview/mPFC-Model-Overview-Full-BackView.jpg)
Bottom module
- Component Overview
- Water reservoir
- Air pump
- 3 Atlas sensors (water temp, pH, EC)
- Heating modules glued to water reservoir (in retrospect, these are pretty useless. Most crops require colder water vs warmer.)
- “Feeding tube” / water level indicator
- Humidifier tank, tube, and mount


Middle Module
- Component Overview
- 50cm3 Acrylic chamber (we had one lying around…we realise this isn’t the cheapest item to source new)
- Opaque acrylic base plate to hold crops
- 1 Intake fan and 1 exhaust fan, with duct plates
- Circulation fan
- Air sensor bubble – CO2 and Temperature/humidity sensor
- Door with locks and hinges
- Base plate (for plants), laser-cut acrylic
- 2 way mirror film on the inside face of the acrylic chamber


Top module
- Component Overview
- 12 custom LED board assemblies (3 LEDs per board)
- Top view camera


Side module
- Component Overview
- Custom Mainboard (ended up not being so useful...see electronics)
- PSU
- 2 custom LED power boards (3 channels per)
- Beaglebone
- Arduino Mega
- Relay Board
- Breadboard
- A ton of wiring



## Guide to 3D Prints
![Bottom Module Overview](/Documentation/ModelOverview/mPFC-Model-Overview-BottomModule.jpg)
### [Bottom module](/Mechanical/Bottom%20Module)
- B.01.A - Bottom Corner Connector, Left (1)
- B.01.B - Bottom Corner Connector, Right (1)
- B.02.A - Bottom Corner Connector, Door, Left (1)
- B.02.B - Bottom Corner Connector, Door, Right (1)
- B.03 - Feeding Tube Holder (1)
- B.04 - Humidifier Tank Mount (1)
- B.05 - Humidifier Mount (1) [2 versions]
- B.06 - Rockwool Carriage (4-12)
- B.07 - Atlas Sensor Holder (1)
- B.08 - Door Handle (1)
- B.09 - Name plate (1)
- B.10.A - Rivet, Small, for Tubing (2)
- B.10.B - Rivet, Large, for Wiring (1)
- B.11 - Safety Cover (1)
---

![Middle Module Overview](/Documentation/ModelOverview/mPFC-Model-Overview-MiddleModule.jpg)
### [Middle module](/Mechanical/Middle%20Module)
- M.01 - Middle Corner Connector (8)
- M.02 - Air Sensor Bubble (1)
- M.03.A - Frame Edge (6)
- M.03.B - Frame Edge, Top Right (1)
- M.03.C - Frame Edge, Bottom Right (1)
- M.04 - Fan Duct (2)
- M.05 - Circulation Fan Mount (1)
- M.06 - Door Hinge (2)
- M.07 - Door Lock (2) [Locking and handle versions]
---

![Top Module Overview](/Documentation/ModelOverview/mPFC-Model-Overview-TopModule.jpg)
### [Top module](/Mechanical/Top%20Module)
- T.01 - Top Corner Connector (4)
- T.02.A - Lighting Board Mount (10)
- T.02.B - Lighting Board Mount, Camera Holder (2)
- T.03 - Middle Support Cap
- T.04 - Top Edge Spacer (8)
---

![Side Module Overview](/Documentation/ModelOverview/mPFC-Model-Overview-SideModule.jpg)
### [Side module](/Mechanical/Side%20Module)
- S.01 - Side Module Connector (16)
- S.02.A - Nut Holder (16)
- S.02.B - Nut Holder, Large (5)
- S.03 - Safety Cover (1)
---

### [Various](/Mechanical/Various)
- V.01 - Screw Nut (8)
- V.02 - Master Key (1)



## Credits

Method PFC v1.0 mechanical designed by Felix Noller and David Mayman