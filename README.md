# Raspberry Pi Pico Awesome List
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a Curation of Raspberry Pi Pico resources. The Raspberry Pi [Pico](https://www.raspberrypi.org/documentation/pico/getting-started/) is a 'low-cost, high-performance microcontroller board with flexible digital interfaces.'

## Contents
- [Documentation](#documentation)
- [Software/Tools](#software-tools)
- [Resources](#resources)
    - [Blogs](#blogs)
    - [Books](#books)
    - [Community](#community)
    - [Projects](#projects)
    - [Tutorials](#tutorials)
    - [Videos](#videos)

## Documentation

- [Getting Started](https://datasheets.raspberrypi.org/pico/getting-started-with-pico.pdf) - The official Pico getting started guide (PDF).
- [Pico SDK C/C++](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-c-sdk.pdf) - The official Pico C/C++ SDK documentation (PDF).
- [Pico SDK MicroPython](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-python-sdk.pdf) - The official MicroPython SDK documentation (PDF).
- [Pico Doxygen](https://raspberrypi.github.io/pico-sdk-doxygen/index.html) - The official 'API level Doxygen documentation for the Raspberry Pi Pico'. Available as a micro-site.
- [Pinout Diagram](https://datasheets.raspberrypi.org/pico/Pico-R3-A4-Pinout.pdf) - The official Pico pinout diagram (PDF).
- [Fritzing Diagram](https://datasheets.raspberrypi.org/pico/Pico-R3-Fritzing.fzpz) - The official Pico Fritzing diagram. WARNING: Will attempt to download file from Raspberry Pi website (.fzpz file).
- [Design Files](https://datasheets.raspberrypi.org/pico/RPi-Pico-R3-PUBLIC-20200119.zip) - The official Pico design files (.zip file). WARNING: Will attempt to download file from Raspberry Pi website.
- [Pico Datasheet](https://datasheets.raspberrypi.org/pico/pico-datasheet.pdf) - The official Pico datasheet (PDF).
- [RP2040 Datasheet](https://datasheets.raspberrypi.org/rp2040/rp2040-datasheet.pdf) - The official RP2040 datasheet (PDF).
- [Hardware Design](https://datasheets.raspberrypi.org/rp2040/hardware-design-with-rp2040.pdf) - The official hardware design with RP2040 (PDF).

## Software/Tools

- [Pico Examples](https://github.com/raspberrypi/pico-examples) - Raspberry Pi Pico SDK examples.
- [Pico MicroPython Examples](https://github.com/raspberrypi/pico-micropython-examples) - Raspberry Pi Pico MicroPython examples.
- [Pico SDK Repo](https://github.com/raspberrypi/pico-sdk) - Official Raspberry Pi Pico SDK repository.
- [Pico C++ Setup Script](https://github.com/raspberrypi/pico-setup/blob/master/pico_setup.sh) - A BASH script for setting up the Pico C++ toolchain on your device.
- [Picotool](https://github.com/raspberrypi/picotool) - 'Picotool is a tool for inspecting RP2040 binaries, and interacting with RP2040 devices when they are in BOOTSEL mode.' 
- [Picoprobe](https://github.com/raspberrypi/picoprobe) - 'It is possible to use one Raspberry Pi Pico to debug another Pico. This is possible via picoprobe, an application that allows a Pico to act as a USB → SWD and UART converter.'
- [Resetting Pico Flash Memory](https://github.com/raspberrypi/pico-examples/blob/master/flash/nuke/nuke.c) - 'There is no way to brick the board through software. However, there are some circumstances where you might want to make sure your Flash memory is empty.'
- [Thonny IDE](https://github.com/raspberrypi/thonny-pico) - Thonny IDE support for the Pico.
- [Pico-Stub](https://github.com/cpwood/Pico-Stub) - MicroPython stubs; 'allowing you to benefit from Python code linting and autocompletion in Visual Studio Code.'
- [Pimoroni Pico](https://github.com/pimoroni/pimoroni-pico) - 'Libraries and examples to support Pimoroni Pico add-ons in C++ and MicroPython.'

## Resources

### Blogs

- [Official Pico Announcement](https://www.raspberrypi.org/blog/raspberry-pi-silicon-pico-now-on-sale/) - The official Raspberry Pi Pico annoucement.
- [MicroPython Book](https://www.raspberrypi.org/blog/new-book-get-started-with-micropython-on-raspberry-pi-pico/) - New book available to help get you started with MicroPython on Raspberry Pi Pico.
- [NeoPixel Dithering](https://www.raspberrypi.org/blog/neopixel-dithering-with-pico/) - HackSpace magazine look at NeoPixels with the Raspberry Pi Pico.
- [Closer Look at RP2040](https://www.cnx-software.com/2021/01/27/a-closer-look-at-raspberry-pi-rp2040-programmable-ios-pio/) - A closer look at Raspberry Pi RP2040 programmable I/Os (PIOs).
- [ML On Raspberry Pi Pico](https://www.arducam.com/raspberry-pi-pico-tensorflow-lite-micro-person-detection-arducam/) - Machine Learning on Raspberry Pi Pico with Tensorflow Lite Micro and Arducam.

### Books

- [MicroPython Pico](https://hackspace.raspberrypi.org/books/micropython-pico) - 'Get Started With MicroPython on Raspberry Pi Pico'.

### Community

### Projects

- [Pico Tetris](https://github.com/rbirkby/picotetris) - 'Tetris on a Raspberry Pi Pico mounted on a Pimoroni Pico Explorer.'
- [Pico Display Colour Change](https://github.com/shane-powell/pico-display-colour-change) - 'A Pico app using Pimoroni's display pack.'
- [Pico Lib for NeoPixels](https://github.com/benevpi/pico_python_ws2812b) - A Raspberry Pi Pico library for using NeoPixels (WS2812b LEDs).
- [TensorFlow Lite Micro](https://github.com/raspberrypi/pico-tflmicro) - An official port of the TensorFlow Lite Micro library for the Pico.
- [Rust Support Crate](https://github.com/devsnek/pio-rs) - Rust support crate for Pico's PIO architecture.
- [morse4pico](https://github.com/slouchd/morse4pico) - Very simple Morse code script in MicroPython for the Raspberry Pi Pico.
- [picoLCD](https://github.com/zadi15/picoLCD) - 'picoLCD is a collection of functions to make interfacing with HD44780 based LCD screens easier on the Raspberry Pi Pico.'
- [Balloon Tracking](http://www.daveakerman.com/?p=2737) - Dave Akerman creates a Raspberry Pi Pico weather balloon tracking device. Code is available at https://github.com/daveake/pico-tracker
- [Pico Snake](https://github.com/Tohaker/pico-snake) - Snake for the Raspberry Pi Pico, running on the Pimoroni Pico Explorer.
- [Annoying Book Mark](https://github.com/rhipps/Annoying-Book-Mark) - A bookmark that counts the amount of time that has passed since you last opened your book.
- [Pico Bird](https://github.com/andreban/pico-bird) - A Flappy Bird implementation for the Raspberry Pi Pico and the Pimoroni Pico Display.
- [Pico Streamdeck](https://github.com/pjgpetecodes/pico-streamdeck) - OBS Controller using a Raspberry Pi Pico and CircuitPython.
- [Pico Invaders](https://github.com/printnplay/Pico-MicroPython/blob/main/picoinvaders.py) - Space Invaders port for the Raspberry Pi Pico.
- [Pico Effects](https://github.com/tuupola/pico_effects) - Old school demo effects for Raspberry Pi Pico.

### Tutorials

- [Control an LED](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico) - Official Raspberry Pi documentation for setting up the Pico. Then controlling an LED with MicroPython.

### Videos

- [Raspberry Pi Pico Launch](https://www.youtube.com/watch?v=o-tRJPCv0GA) - Raspberry Pi Foundation's Pico launch video.
- [BBC Micro Emulation](https://www.youtube.com/watch?v=WaPJmCgseQw) - 'Full-speed high-fidelity BBC Micro emulation on a (slightly) overclocked Raspberry Pi Pico'
- [Geerling Pico Review](https://www.youtube.com/watch?v=dUCgYXF01Do) - YouTuber Jeff Geerling reviews Raspberry Pi Pico.
- [Hackster Pico Unboxing](https://www.youtube.com/watch?v=qHT9UR8MTrE) - Hackster.io partake in a recorded Raspberry Pi Pico unboxing.
- [ETA PRIME Pico First Look](https://www.youtube.com/watch?v=IIBtAQQOZ90) - YouTuber ETA PRIME reviews Raspberry Pi Pico. 
