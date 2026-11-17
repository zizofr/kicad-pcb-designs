# KiCad PCB Designs

Two PCB projects designed in KiCad: a digital voltmeter and a 220 V AC LED lamp. Each folder contains the schematic, the PCB layout and 3D renders.

## 1. Digital voltmeter (`voltmeter/`)

A voltmeter board built around an **ATmega328P** with a 16 MHz crystal and a 16x2 LCD.

- **Power:** 7805 regulator with reverse-polarity protection
- **Input stage:** resistor divider with a fuse, clamping diodes and a 5.1 V zener to protect the ADC
- **Programming:** ICSP header
- **Layout:** double-sided PCB with routed traces and a ground pour

**Status:** designed in KiCad. [Add whether you assembled and tested it, and the measurement range]

## 2. LED lamp (`led-lamp/`)

A compact LED lamp powered from the 220 V AC mains.

- **Rectification:** MB6S bridge rectifier
- **Lighting:** series string of SMD LEDs
- **Passive parts:** current-limiting and bleeder resistors, smoothing capacitors

**Status:** designed in KiCad. [Add whether you built or tested it]

> ⚠️ **Safety warning:** this circuit connects directly to 220 V mains and has no galvanic isolation. Every part of the circuit can be at mains potential. Do not build or touch it unless you know how to work safely with mains voltage. It is shared for educational purposes only.

## Tools

KiCad (schematic capture, PCB layout, 3D viewer)

## Author

Mohamed Aziz Farhani, IoT Engineering Student at ISITCom Hammam Sousse
[LinkedIn](https://www.linkedin.com/in/mohamed-aziz-farhani-18540a33a)
