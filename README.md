
# Music Synchronized LED Light System
*A microcontroller-based LED strip controller that reacts to music.*

This is a mini project from my **Microprocessors and microcontrollers** course. It run on an **8051 microcontroller**, taking analog input from sound sensor and controlling the LED behaviour.


## Features

- Control a WS2812B LED strip (16 LEDs) using single-wire PWM
- LED effects automatically cycle after a set interval
- Real-time sound input processing with a microphone/sound sensor


## Usage
To set your favorite LED color manually, use the
`generating_send_color.cpp` code.

1. Compile and run `generating_send_color.cpp`
2. Enter an RGB value in the order: **G R B** (0–255 each)
3. Press **Enter**
4. A file called `sus.txt` will be generated with the color data

### Example
`255 255 255` This will output `sus.txt` containing the color white. 


## Schematic
![The following schematic shows how the sound sensor and LED strip are connected to the microcontroller:](/Images/schematic.png)