# ESPHOME Light Switches
This folder contains code and schematics for esp based light switches

## GoKlug TuYa 1-3 Way Switch
![PCB of switch](/ESPHome_LightSwitch/media/goklug_tuya_pcb.jpg)
The GoKlug TuYa Switch uses the TYWE3S ESP07 Clone. It can be a bit tricky to flash this one over serial, for me using dout as flash mode worked most of the time.
Also leaving the serial wires connected to a programmer often gets the module into a boot loop with exeptions. Program the module while it is soldered in the pcb and have the touch buttons facing up
