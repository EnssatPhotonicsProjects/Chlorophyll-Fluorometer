
<p align="center">
  <img src="images/logo_enssat.png" alt="ENSSAT Logo" width="200"/>
</p>

# Chlorophyll-Fluorometer

## Description

This project aims to develop a portable and low-cost fluorometer for detecting chlorophyll a concentration, a key indicator of phytoplankton presence. The project is conducted by students from ENSSAT in collaboration with the European Institute for Marine Studies (IUEM) and is part of an open-source initiative to facilitate easy and cost-effective replication of the device.

This GitHub repository is intended to provide all necessary resources and instructions to reproduce the product.

## Features

- Measures chlorophyll a concentration in the range of [1-50] µg/L.
- Low-cost (approximately $200), low-tech, and open-source design.
- Super

## Functionality

The device operates on the principle of fluorescence, where chlorophyll emits light upon excitation. The Arduino board enables modulation and demodulation to eliminate ambient light, thereby enhancing signal quality. A red filter is used to prevent the detection of light used to stimulate chlorophyll, allowing only the desired wavelengths to pass through to the photodiode. This setup improves the accuracy of measurements by reducing interference from unwanted light sources.

## Components

the main components are:

| Component | Description |
|-----------|-------------|
| LED | Light Emitting Diode for excitation |
| Photodiode | Detects fluorescence |
| Arduino | Microcontroller for processing |
| ADC | Analog to Digital Converter |
| Transistor | LED modulation |
| Amplifier | Enhances signal |

For a detailed list of components with the références, please refer to the [Components List](components.md).

## Construction of the fluorimeter

### Prerequisites

- Arduino IDE
- Electronic components
- 3D printer
- Soldering equipment
- Tupperware

### Installation Steps

1. **Clone the Repository:**

   ```bash
   git clone [REPOSITORY_URL]
   ```

### Assemble the Electronic Components

For component assembly, we provide a PCB file and a schematic diagram. It is possible to do everything with a breadboard without PCB.

- **Technical Drawing:** A detailed schematic diagram is provided here: [Schematic.pdf](path/to/Schematic.pdf). This diagram includes component placement and connection details.

- **PCB File:** The PCB design file is available in the repository: [PCB](). Use this file to order a PCB from a manufacturer or print it if you have the necessary equipment.

### Assemble Support

- Use the provided STL files to print the necessary supports. Links to the files will be provided, including files for the [LED+photodiode](STL_file_ready_to_3D_printing/support_led_photodiode.stl) and the [board support](STL_file_ready_to_3D_printing/support_arduino.stl).

### Arduino

- Open the `.ino` file in the Arduino IDE and upload it to your Arduino board. There will be multiple codes available to test the correct connection. The provided codes are modular but the main one allows displaying the photodiode current in nA.

### Calibration

- Follow the calibration protocol described in the documentation to adjust the fluorometer according to local conditions.

## Contribution

Contributions to this project are welcome. Here's how you can contribute:

1. **Fork the Repository** and create your branch:

   ```bash
   git checkout -b my-new-feature
   ```

2. **Make Your Changes** and test them thoroughly.

3. **Submit a Pull Request** with a detailed description of your changes.

## License

This project is licensed under [License Name]. Please see the `LICENSE` file for more details.
