# Ultimaker 2+ BTT Manta M5P Klipper mod 
The Ultimaker 2 has a fantastic mechanical design that keeps up with current coreXY motion systems. The stiff and lightweight gantry is capable of high acceleration figures with little ringing. 

With that said, electronics improved a lot since 2014.
The Ultimaker 8 bit Arduino based controller, running an old version of Merlin, is really outdated.
These days, 64 bit ARM computers running Klipper, connected to fast 32 bit controllers offer input shaping (reduces ringing), pressure advance (tunes for nozzle pressure), wireless connectivity, silent steppers etc.

The Ultimaker mainboard also has several design flaws that cause visible layer banding, inaccurate temperature readings and LED flickering while the bed heater is running.

Here you can find the instructions, components, STL files and printer.cfg to convert your Ultimaker 2 to Klipper.

## Recommended parts (BOM) - Aliexpress
- BIGTREETECH Manta M5P + CB1 (heatsink) + TMC2209
- BIGTREETECH MAX31865 V2.0 PT100 amplifier
- NTC100K thermistor
- Meanwell LRS-350-24 power supply
- FYSETC POM TR8x8 lead screw nut (recommended)
