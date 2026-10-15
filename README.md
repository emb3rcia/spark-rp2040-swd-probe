# spark-rp2040-swd-probe

> [!WARNING]
> This project is under active development. Firmware is not started.
> Currently, board is not confirmed to be working nor yet manufactured

# Navigation

- [About the project](#about-the-project)
  - [Motivation](#motivation)
  - [Usage](#usage)
  - [Directory overview](#directory-overview)
  - [Development tools](#development-tools)
  - [Features](#features)
- [Images](#images)
- [License](#license)
- [AI declaration](#ai-declaration)

# About the project

spark-rp2040-swd-probe is SWD probe with support for SWO, as well as BOOT_SEL support incoming via add-on board, based on Raspberry Pi Foundation's `debug-probe` firmware.

## Motivation

I wanted to make cheap, open source and readily available version of SWD probes available commercialy, but with level shifters, LEDs etc.

## Usage

Firmware implementation as well as software support isn't yet done or verified.

## Directory overview

- `/Firmware` - adapted `debug-probe` firmware (PLANNED)
- `/PCB` - editable KiCad project
- `/Gerbers` - generated PCB fabrication files
- `/Images` - project images and renders
- `/Licenses` - license texts

## Development tools

- KiCad for EDA work
- Visual Studio Code for firmware adaptation
- FreeCAD for enclosures

## Features

- SWO capture
- Level shifters down to 1V2 (1.2V)
- Status and activity LEDs
- Target connected LED
- Target voltage LED

# Images

Front
![Front](/Images/FRONT.png)

# License

This repository contains material under multiple licenses. Individual file-level notices and third-party licenses take precedence over these directory-level defaults.

## Hardware license

Original files under `/PCB`, and `/Gerbers` are licensed under the CERN Open
Hardware Licence Version 2 – Weakly Reciprocal.

See `/Licenses/CERN-OHL-W-2.0.txt` for full terms.

## Firmware license

Original files under `/Firmware` are licensed under the Apache License 2.0.

See `/Licenses/Apache-2.0.txt` for full terms.

## Documentation and media

The root `README.md`, and original images,
renders, and photographs under `/Images` are licensed under the Creative Commons Attribution 4.0 International license.

See `/Licenses/CC-BY-4.0.txt` for full terms.

Only material owned by the project is covered. Third-party assets retain their original licenses.

Project names, logos, and wordmarks are not licensed unless explicitly stated.

# AI Declaration

ChatGPT was used in process of making this project.

Uses of it include debugging help, datasheet key information extraction, validation of code and others.

© 2026 emb3rcia

- Firmware: Apache-2.0
- Hardware and manufacturable CAD: CERN-OHL-W-2.0
- Documentation and original media: CC-BY-4.0
