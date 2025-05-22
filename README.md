# EVAM 1 Electronics Modules

> Design and manufacturing files for the EVAM 1's electrical and CAN bus system

<p align="center">
<img src="https://user-images.githubusercontent.com/6837599/138331854-9dfa00b7-021b-4b2a-a48f-78b1f74af131.png" width="20%" \>
</p>


- [x] 🏎️ Automotive Hardware
- [ ] 🛞 Automotive Software
- [ ] 🖥️ Supporting Software and Simulations
- [ ] 📚 Code Library
- [ ] 🛠 Helper Script
- [x] 📖 Documentation / Datasheets
- [ ] ❓ Miscellaneous / Uncategorized

This repository contains the hardware design and manufacturing files for the EVAM 1's electrical system.  


## Directories

* `CANBus 2/Design` - Design files in KiCAD format
    * `/APPS` - Throttle position sensor PCB
    * `/BMS` - Battery Management System PCB
    * `/ECU` - Engine Control Unit PCB
    * `/HUD` - Heads up Display PCB
    * `/MCU_Double` - Motor Control Unit, double motor (for front motors)
    * `/MCU_Single` - Motor Control Unit, single motor (for rear motors)
    * `/SAS` - Steering Angle Sensor, originally meant for torque vectoring. Currently not used
* `CANBus 2/Manufacturing` - Manufacturing files (BOM, placement, and Gerbers)
* `CANBus 2/Electrical Layout` - Electrical layout design files, including block diagrams, to describe the high level overview of the entire electrical system
* `CANBus 2/Harness` - Cable harness design files and pictorial diagrams
* `Datasheets` - All the datasheets for the various components employed in the vehicle


## Documentation

Please refer to EVAM internal OneDrive for further documentation, including specific datasheets on the electrical system components


## Caveats

No known caveats yet


## Known issues

No known issues yet


## Contributing

If you encounter any issues with this repository, please do not hesitate to open an issue.

