# klipper-SKR-mini-E3-V1.2-BLtouch-BMG

My copy paste effort to get my ender 3 with SKR mini E3 V1.2 to work with Klipper.

Other custom parts I added to the printer and config are:
- BLtouch clone using the Z header on the board
- Trianglelab BMG mini clone

Running on:
- Ender 3 V1 with LCD Matrix screen
- Hardware: RPI 4 2GB
- OS: mainsailos v2.4.0
- Klipper version: v0.10.0-639-g1b56a63a
- Cura 5.2.1

calculate rotation_distance: https://3dprintbeginner.com/rotation-distance-calculator/


Cura start G CODE: START_PRINT BED_TEMP={material_bed_temperature_layer_0} EXTRUDER_TEMP={material_print_temperature_layer_0}
Cura stop G code:END_PRINT
