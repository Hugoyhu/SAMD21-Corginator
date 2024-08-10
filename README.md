# SAMD21-Corginator

The Corginator _v2_ is an updated version of the original Corginator (which had an ATMEGA328P microcontroller). Here's what's new:
* ATMega328P replaced with ATSAMD21G18 (faster, more memory, more storage, and more bits!)
* ICSP programming replaced with keyed SWD header 
* Bulky USB Type-B replaced with USB Type-C connector
* Arduino Nano form factor replaced with Adafruit Feather form factor
* Li-poly single cell battery charging enabled with Microchip MCP73831
* Smaller and lighter design

# Open Source Hardware

The Corginator v2 is open source hardware. This design was created in [KiCAD](https://www.kicad.org), an FOSS schematic capture and PCB layout / routing software. While schematics are provided in PDF format, you will need the latest version of KiCAD (v8 or above) to directly view and modify the schematic and PCB. 

## Schematic
![PNG of Schematic Capture](https://github.com/user-attachments/assets/67949de5-8256-40bd-81b0-b063c1746e23)

## PCB 
![Image of Assembled Corginator v2](https://www.hugohu.me/media/Corginator-SAMD21G18-Macro.jpg)

# Attribution 

This design uses the [Adafruit Feather M0](https://www.adafruit.com/product/2772) as a reference design for both the SAMD21 and battery charging. I also used their [wonderful tutorial](https://learn.adafruit.com/how-to-program-samd-bootloaders/overview) to flash a bootloader onto the Corginator with my Segger J-link EDU. 

To support Adafruit's open-source hardware _and_ software development, please consider using their USA-designed & manufacturered products in your next project.



