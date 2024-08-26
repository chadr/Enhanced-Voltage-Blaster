# Enhanced Voltage Blaster
 A (slightly) enhanced version of the original Voltage Blaster by PhilsComputerLab and Necroware [here](https://youtu.be/y1-0giyLQIY).

![Finished Voltage Blaster](https://github.com/chadr/Enhanced-Voltage-Blaster/blob/main/img/blaster.jpg?raw=true)

**Enhancements:**
* Diodes protect regulator from reverse polarity and reverse bias. Prevents soundcard-frying over voltage.
* Four LEDs show presence of the four main power rails on the ISA bus.
* Dual copper heatsink pads embedded into PCB design to keep regulator cool.
* Jumper to disable Voltage Blaster without removal. Can be used to verify lack of (-)5V on ISA bus.

The datasheet for the 79xx series negative regulators strongly recommend two protection diodes. PCs get shutdown suddenly and sound cards have lots of capacitance. The exact two situations described here.
![Protection diode info](https://github.com/chadr/Enhanced-Voltage-Blaster/blob/main/img/protection_diodes.jpg?raw=true)

**Bill of Materials**
**Item**|**Qty**|**MFG Part Num**|**Mouser Part Num**
:-----:|:-----:|:-----:|:-----:
Neg 5V Linear Regulator|1|MC79M05CDT|863-MC79M05CDT
22uF 35V Electrolytic Capacitor|2|860010572003|710-860010572003
5mm Red LED Diffused|4|WP7113ID|604-WP7113ID
330R Metal Film Resistor 1%|2|MFR-25FRF52-330R|603-MFR-25FRF52-330R
1K Metal Film Resistor 1%|2|MFR-25FRF52-1K|603-MFR-25FRF52-1K
Schottky Diode 40 Volt 1.0 Amp|2|SB140-E3/73|625-SB140-E3/73

<a href="https://www.tindie.com/stores/pcrestoration/?ref=offsite_badges&utm_source=sellers_PCRestoration&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>
