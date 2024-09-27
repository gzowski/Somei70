# Somei70

70 key keyboard with alternative layout similar to that of split keyboards.
![Somei70](https://github.com/gzowski/somei70/blob/main/images/pcb.jpg)

More photos can be found on my own site: https://www.gzowski.co.uk

PCB will eventually be available for purchase.

## Features
* 70 Key layout
* Per key LED's for Row 1 (numbers and backspace)
* Return/Enter key relocated beside Spacebar
* Slightly reduced stagger on row 4, allowing for additional key after right shift
* 128x32 OLED Display, configurable in code, by default displays logo
* QMK Firmware with VIA support
* OLED Modes: triple press ESC in quick succession to switch between logo and stats mode.

## Parts

| Part | Quantity     | Description                |
| :-------- | :------- | :------------------------- |
| Diodes| 70 | SMD 1N4148W |
| Microcontroller | 1 | Frood, Elite-Pi or other compatible RP2040 Pro Micro with additional pins |
| Switches | 70 | MX switches |
| Kailh MX sockets | 70 | Hotswap sockets |
| Keycaps | 70 | MX compatible keycaps |
| Stabalisers | 4 | PCB screw mounted stabalisers |
| LED Diodes | 14 | SK6812 MINI-E |

## Optional Parts

| Part | Quantity     | Description                |
| :-------- | :------- | :------------------------- |
| Top Plate | 1 | Lasercut or 3D print options in Plates folder |
| Base Plate | 1 | Lasercut or 3D print options in Plates folder |
| M2 Standoff | 5 | M2x8mm |
| M2 Standoff | 1 | M2x3mm/4mm/5mm |
| M2 Screws | 12 | M2x6mm |

## Build Guide

Guide images shown below build instructions.

1. Place the board upside down, this is the side without the graphics on the PCB
2. Start by placing down each of the Kailh MX sockets. (Purple on Guide Images)
   - Solder each of the legs of the Kailh sockets to the PCB
3. Next is to place each of the diodes down, a pair of tweezers can help here with holding them in place.
   - Ensure orientation is correct when placing down, (Red on Guide Images, notice orientation marking in red)
4. Next is to solder down the SK6812 MINI-E diodes if your choosing to add LED's (Green on guide images, yellow circle indicates ground)
5. Turn the PCB over.
6. Install the stabalisers (Top left, circled in white show screw placement)
7. It's recommended to flash your controller with firmware beforehand especially if not using hot swappable pins on your controller, once soldered it can be harder to put the controller into boot mode, depending on the microcontroller (some have contacts for boot on the rear)
8. Place down the PCB face down, depending on your mounting method it'll differ sligthly.
   - Solder pins to the controller and then turn the main PCB over and solder the controller onto the PCB.
9. If opting to use an OLED Display, this will sit on top of the micro controller, turn the PCB onto it's rear and solder the OLED display legs to the PCB. (Lower left corner, circled in white on guide images)
10. Power the PCB and make sure it all works, by default if you've installed the OLED and LED's they should both light up.

That's it for the PCB assembly, everything from here is optional, i've provided 3d models and cutouts for the top plate and base plate.
If not using a top plate (not advisable), then you can continue to insert your switches.

![Guide Images](https://github.com/gzowski/somei70/blob/main/images/guideimages.jpg)

## Default Key Layout


