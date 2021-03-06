# LittlevGL ported boards and microcontrollers

This repository contains projects where [LittlevGL](https://littlevgl.com) is configures for a development board or microcontroller. 

Contributing is very welcome! Plaase, share with others if you used LittlevGL with a new board or MCU.

## Usage
1. Clone the repository somewhere: `git clone https://github.com/littlevgl/lv_boards.git`
2. Step into the repository: `cd lv_boards`
3. Initalize the submodules: `git submodule update --init`
4. Copy/Paste a project where you want to use it (e.g. IDE workspace)

## Porojects

### arduino_library
LittlevGL as an Arduino library. 
Copy *arduino_library/littelvgl* to your library folder
Check the *lvlgl_test* sketch to see the proting and usage

### stm32f429_discovery_no_os
Cheap development board with 240x320 TFT, Resistive touch pad, 180 MHz MCU with 256kB RAM + 64 MBit SDRAM and GPU.
The CubeMX drivers are used to initilaize the peripheries. In *hal_stm_lvgl/tft/tft.h* you can enable/disable external frame buffer placement and GPU usage.

### linux_frame_buffer
Directly use Linux fame buffer (e.g. /dev/fb0) as frame buffer. Demonstrates the usage winth embedded Linux systems. The project is created in Eclipse CDT. Learn more here: [LittlevGL Blog Post](https://littlevgl.com/blog/23/embedded-gui-using-linux-frame-buffer-device-with-littlevgl)

