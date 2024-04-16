# senseBox MCU S2 x PlatformIO

This repository is an example project for the senseBox MCU S2 with PlatformIO. It just prints "Hello semseBox" on the display

## Hardware

You need the following hardware to run this project:

- senseBox MCU S2
- senseBox Display
- Qwiic Cable
- USB-C Cable

## Install PlatformIO

To install PlatformIO, follow the instructions on the [PlatformIO website](https://platformio.org/install).

_I personally recommend to create a new VSCode Profile for PlatformIO, so you can easily switch between PlatformIO and other VSCode extensions._

## Clone this repository

Clone this repository to your local machine.

```bash
git clone git@github.com:sensebox/sensebox-mcu-s2-platformio.git
```

## Open the project in VSCode

Open the project in VSCode.

```bash
code sensebox-mcu-s2-platformio
```

## Build the project

Build the project by clicking the `Build (✔)` button in the lower toolbar, pressing `Ctrl + Alt + B` or by running the following command in the terminal.

```bash
pio run
```

## Upload the project

Upload the project by clicking the `Upload (→)` button in the lower toolbar, pressing `Ctrl + Alt + U` or by running the following command in the terminal.

```bash
pio run --target upload
```
