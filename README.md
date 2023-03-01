# bioinsprobo - github repository
## Install and Setup
The Raspberry Pi Pico platform has several prerequisites that require install and setup which is especially convoluted when not on Linux/Raspberry Pi OS.

Shawn Hymel has the most comprehensive guide to installing, setting up and verifying the Pico C/C++ Toolchain. His videos on setting up VS Code and the Picoprobe debugger are the most comprehensive around.

[Getting Started with Pico](https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf) is the Raspberry Pi Foundation's official documentation for getting started with C/C++ Development. I would recommend following it for simplicity on Linux, Raspberry Pi OS, and Mac OS, however the setup on Windows is convoluted and requires the install of Build Tools for Visual Studio (at minimum 6GBs) and requires startup of VS Code through the Build tools command line every time so that NMake Makefiles can be used. Alternatively using MinGW Makefiles and following the below instructions the development environment can be streamlined and run through visual studio normally as with any other development environment.
### ARM Cross-compiler (arm-none-eabi), MinGW, CMake, Python, Pico-SDK and Pico-Examples
[How to Set Up Raspberry Pi Pico C/C++ Toolchain on Windows with VS Code](https://shawnhymel.com/2096/how-to-set-up-raspberry-pi-pico-c-c-toolchain-on-windows-with-vs-code/)
### Visual Studio Code
[Intro to Raspberry Pi Pico and RP2040 - C/C++ Part 1: VS Code and Blink | Digi-Key Electronics](https://www.youtube.com/watch?v=B5rQSoOmR5w)
### OpenOCD and Cortex-Debug
[Intro to Raspberry Pi Pico and RP2040 - C/C++ Part 2: Debug with Picoprobe | Digi-Key Electronics](https://www.youtube.com/watch?v=jnC5LrTx470)
### Cloning the Repository
## Directory Structure
### src
Project source code and headers written for project applications.
### lib
Contains externally linked libraries used in applications.
### apps
Directory for executables for the project.
