# Paul - Custom Split Keyboard

This project contains the PCB and Gerber files for a custom split keyboard, designed from the ground up using **KiCad** and **Ergogen**. Paul is a 42-key reversible PCB layout, tailored for ergonomic and customizable typing experiences. I currently use this keyboard as my primary device, and it has been a rewarding project from both a hardware and software perspective.

## Features
- **42-Key Reversible PCB Layout**: Designed to be efficient and minimal, the PCB supports both left and right halves of the split keyboard.
- **Custom Key Mapping Software**: Programmed using **QMK-MSYS**, **C++**, and **Python** for full customization of key mappings.
- **OLED Display**: Includes an OLED screen for additional visual feedback.
- **TRRS Jacks**: Easy connectivity between the two halves via TRRS jacks.
- **Fully Customizable Keycaps and Switches**: Tailored for your preferences.

## Hardware
- **PCB Design**: Created using **KiCad** and **Ergogen**, the PCB is compact and optimized for ergonomic usage.
- **Components Soldered**:
  - Resistors
  - Transistors
  - OLED Screen
  - TRRS Jacks
  - Keycaps
- **3D-Printed Case**: Designed and printed custom cases to house the PCB.

## Software
The keyboard firmware was developed using **Visual Studio** and leverages **QMK** for advanced key remapping and functionality. Here are some key details:
- **QMK-MSYS**: The keyboard firmware is programmable through QMK, allowing for endless customization of the key layout.
- **C++ and Python**: Used in conjunction with QMK for configuring macros, lighting, and OLED display outputs.

## PCB and Gerber Files
All the files necessary to fabricate your own Paul split keyboard are located in the `pcb/` directory of this repository.

## Getting Started
1. **Download the Gerber Files**: These are necessary for manufacturing the PCB. You can upload these files to any PCB manufacturer of your choice.
2. **Solder the Components**: Refer to the provided PCB design for where to solder the resistors, transistors, OLED screens, TRRS jacks, and key switches.
3. **Flash the Firmware**: Once the PCB is assembled, use QMK to program the firmware. Follow the instructions in the [QMK documentation](https://docs.qmk.fm/#/newbs) to get started with flashing.
4. **Assemble the Keyboard**: Use the provided 3D models to print a case that houses your keyboard and secures the components.

## Usage
This keyboard is fully customizable, and you can program custom keymaps to fit your workflow. Paul is currently in use as my daily keyboard, demonstrating its durability and functionality.
