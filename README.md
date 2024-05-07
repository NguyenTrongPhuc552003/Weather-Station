# Weather Station with STM32F411RET6, BLE HM-10, and DHT11

This project implements a weather station using the STM32F411RET6 microcontroller, BLE HM-10 module, and DHT11 temperature and humidity sensor. It collects temperature and humidity data from the DHT11 sensor and transmits it via Bluetooth Low Energy (BLE) to a terminal window for display.

## Features

- Collects temperature and humidity data from the DHT11 sensor.
- Transmits data wirelessly via BLE using the HM-10 module.
- Displays data on a terminal window.

## Hardware Requirements

- STM32F411RET6 microcontroller.
- BLE HM-10 module.
- DHT11 temperature and humidity sensor.
- Other necessary electronic components (e.g., resistors, wires, etc.).

## Software Requirements

- STM32CubeIDE or similar IDE for STM32 development.
- STM32CubeMX for configuring peripherals.
- Libraries for STM32F4 series microcontrollers.
- Terminal emulator software for displaying data (e.g., PuTTY, Tera Term, etc.).

## Setup

1. Connect the STM32F411RET6 microcontroller, BLE HM-10 module, and DHT11 sensor according to the wiring diagram provided in the documentation or source code.
2. Configure the project in STM32CubeMX or similar software, ensuring proper pin configurations and peripheral settings.
3. Import the project into your IDE (e.g., STM32CubeIDE).
4. Build and flash the firmware onto the STM32F411RET6 microcontroller.
5. Install a terminal emulator software on your computer.
6. Power on the weather station and open the terminal emulator to receive data.

## Usage

1. Power on the weather station.
2. Open the terminal emulator and connect to the BLE HM-10 module.
3. The temperature and humidity data should start streaming to the terminal window.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
