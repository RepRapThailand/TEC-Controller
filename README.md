
# Laser4DIY TEC Controller

![alt text](hardware/finalboard.jpg "TEC Controller board")

This is the repository for the TEC (Thermo Electrical Cooling) controller used in the [Laser4DIY project](http://www.laser4diy.org/).

## Specs

* Designed as a shield for the Arduino Due
* 2-channel TEC controller, driving peltier elements up to 106W heat transfer capacity per channel (12A at 15.5V)
* 2 boards can be stacked for a 4-channel TEC controller, driven by a single Arduino Due

## Repository Layout

```
+ Firmware                      firmware directory
| + Firmware.ino                Main Arduino firmware source code file
| + functions_PWM_DAC.ino       source code
| + LICENSE.txt                 license for the fimware
| + main_loop.ino               source code
| + main_setup.ino              source code
| + README.txt                  firmware readme
+ Hardware                      hardware directory
| + cern_ohl_v_1_2_howto.pdf    Howto for the used hardware license
| + CHANGES.txt                 list of hardware changes
| + finalboard.jpg              photo of the final board
| + LICENSE.txt                 license for the hardware
| + README.txt                  hardware readme
| + schematic.png               schematic
| + TEC-Controller.brd          board layout
| + TEC-Controller.sch          schematic
```

## Documentation

The TEC Controller is documented at 
https://wiki.fablab-muenchen.de/display/WIKI/LASER4DIY+-+TEC+Controller

## License

The hardware documentation is licensed under CERN OHL v.1.2.
The firmware is licensed under GPLv3.
For details see licensing info in the respective sub directories

---

Copyright FabLab M�nchen e.V. 2018
Laser4DIY is sponsored by the Federal Ministry of Education and Research

 