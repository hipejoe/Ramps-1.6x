Ramps-1.6 or so
===========

forked from ultimachine/Ramps 1.4

terminated AUX doe to space

added libs for tmc2130 watterot with conf0 installed 
add E2
chanded libs f tmc2130 to not use space of unused headers
added supression to endstops but removed 2nd endstop for axis (has tmc2130 so only Z and probe may need one.
re added 2servos
upgraded to 4thermoistors


integrated my previous fan extendr to 5 external outputs
removed VIN (toDO! check arduinos power consumption etc)
changed package or reset + external reset 

changed few Packages to match order
Orderd First Batch PCBs to test

RAMPS 1.6.3 
Got one wirestumb on Zmin fixed
Changed Pins Back to HWSPI 
Added I2C pin Header and HW SPI breakout
added 5vin 
