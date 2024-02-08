# SP5-V3-Marlin
TwoTrees Sapphire SP5-V3 - Marlin 2.1.x
Configuration for the SP5-V3 , running on Marlin 2.1.x

Various features of Marlin were added:
Linear Advance
Input Shaping
PID Autotune (Hotend only)
Now running X, Y & Z in 64 microsteps, E, at 16.

The bed was "reduced" due to my use of bed clips (instead of the awful adhesive that cames with the glass-bed), but, if you still use the original setup change the following:
#define Y_BED_SIZE 270 to #define Y_BED_SIZE 295

#define Y_MIN_POS -15 to #define Y_MIN_POS -5

Filament runout sensor is off, since i couldn't find the pin used for the feature.

