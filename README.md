< ongoing project >
# Ultimaker 2+ BTT Manta M5P Klipper mod 
The Ultimaker 2 has a fantastic mechanical design that keeps up with current coreXY motion systems. The stiff and lightweight gantry is capable of high acceleration figures with little ringing. 

With that said, electronics improved a lot since 2014.
The Ultimaker 8 bit Arduino based controller, running an old version of Merlin, is really outdated.
These days, 64 bit ARM computers running Klipper, connected to fast 32 bit controllers offer input shaping (reduces ringing), pressure advance (tunes for nozzle pressure), wireless connectivity, silent steppers etc.

The Ultimaker mainboard also has several design flaws that cause visible layer banding, inaccurate temperature readings and LED flickering while the bed heater is running. The old controller also uses "bang-bang" to maintain heatbed temperatures (turns on, overshoots, turns off, undershoots, etc...). The new controller allows for precise PID temperature control.

Here you can find the instructions, components, STL files and printer.cfg to convert your Ultimaker 2 to Klipper.
BTT M5P Github: https://github.com/bigtreetech/Manta-M5P

## Parts requirements:
- The Ultimaker Heatbed is rated for 180W (24V, 7.5A). The print head heater is rated for 25W. Peak power during heating will surpass 200W. Average power during printing will probably be around 100W for PLA and 150-200W for ABS. A 350W power supply was chosen.
- The hotend thermistor can be replaced easily but the heatbed thermistor is soldered. The Manta M5P was chosen to allow a MAX31865 SPI amplifier to connect the PT100 heatbed thermistor.
- The POM nut does not require lubrication and should offer a tight fit to prevent backlash.

## Recommended parts (BOM) - Aliexpress
- BIGTREETECH Manta M5P + CB1 (heatsink) + TMC2209
- BIGTREETECH MAX31865 V2.0 PT100 amplifier
- NTC100K thermistor
- Meanwell LRS-350-24 power supply
- FYSETC POM TR8x8 lead screw nut (recommended)
- M3 screw kit with nuts
- Crimp tool for molex, ferrule and insulated terminals


![Controller installed with adapter plate](https://github.com/nadavelkabets/Ultimaker-2-BTT-Manta-M5P-Klipper/blob/main/Manta_installed.jpg)
