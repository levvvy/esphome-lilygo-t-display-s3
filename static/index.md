# About

# Lilygo T-Display-S3 ESPHome Implementation 🌐🚀

## Table of Contents

- [Features and Requirements](#features-and-requirements)
- [Hardware Setup](#hardware-setup)
- [Software Setup](#software-setup)
- [Troubleshooting](#troubleshooting)
- [License and Credits](#license-and-credits)

## Features and Requirements 🔧💻

### Features:
* ESP32-S3 chip support
* Integration with the ST7789VW 1.14" 135x240 TFT LCD display
* Display of various sensor data, time, and custom text
* Configurable display layout and themes
* Over-the-Air (OTA) firmware updates
* Support for Home Assistant integration

### Requirements:
* Lilygo T-Display-S3 board
* Micro-USB cable for programming and power supply
* ESPHome (version 2022.02.0 or later)
* Home Assistant (optional, for integration)

⚠️ Note: This implementation has been tested with the Lilygo T-Display-S3 board. It may not be compatible with other versions or clones of the T-Display board.

🔗 Official Repository: [https://github.com/levvvy/esphome-lilygo-t-display-s3](https://github.com/levvvy/esphome-lilygo-t-display-s3)

## Table of Contents

- [Features and Requirements](#features-and-requirements)
- [Hardware Setup](#hardware-setup)
- [Software Setup](#software-setup)
- [Troubleshooting](#troubleshooting)
- [License and Credits](#license-and-credits)

<details>
  <summary>Click to expand!</summary>
  
  ## Features and Requirements 🔧💻

  ### Features:
  * ESP32-S3 chip support
  * Integration with the ST7789V 1.9″ 320×170 Color IPS TFT Display
  * Display of various sensor data, time, and custom text
  * Configurable display layout and themes
  * Over-the-Air (OTA) firmware updates
  * Support for Home Assistant integration

  ### Requirements:
  * Lilygo T-Display-S3 board
  * Micro-USB cable for programming and power supply
  * ESPHome (version 2022.02.0 or later)
  * Home Assistant (optional, for integration)

  ⚠️ Note: This implementation has been tested with the Lilygo T-Display-S3 board. It may not be compatible with other versions or clones of the T-Display board.

  ## Hardware Setup 🔌🔧

  1. Connect the Lilygo T-Display-S3 board to your computer using a Micro-USB cable. Ensure that the board is powered up and recognized by your computer.
  2. Check for any visible damage on the board, display, or components before proceeding. If you find any issues, contact the supplier or manufacturer for assistance.
  3. (Optional) If you plan to integrate additional sensors or peripherals with the T-Display-S3, follow the manufacturer's documentation to connect and configure them.
  4. Make sure the board is properly connected and powered during the entire software setup process.

  ## Troubleshooting 🛠️🔍

  If you encounter any issues during the setup or usage of the Lilygo T-Display-S3 with ESPHome, try the following steps:

  1. Double-check your hardware connections and ensure the board is properly powered.
  2. Verify your Wi-Fi credentials and other sensitive information in the `secrets.yaml` file.
  3. Review the configuration in `esphome-lilygo-t-display-s3.yaml.yaml`, ensuring there are no errors or inconsistencies.
  4. Check the ESPHome logs for any error messages or warnings. Use the following command to view the logs, replacing `<your-device-name>` with the name you chose for your device:
     ```
     esphome logs -d <your-device-name> lilygo_t_display_s3.yaml
     ```

  5. Consult the [ESPHome documentation](https://esphome.io/) and [Lilygo T-Display-S3 GitHub documentation](https://github.com/Xinyuan-LilyGO/T-Display-S3) for further information and guidance.

  6. If you are still experiencing issues, please create a [new issue on the GitHub repository](https://github.com/levvvy/esphome-lilygo-t-display-s3/issues), providing as much detail as possible about your problem.

  ## Task List

  - [Soon™] Create Lilygo T-Display-S3 ESPHome implementation
  - [x] Write documentation
  - [x] Publish the GitHub repository
  - [ ] Add more example configurations

  ## License and Credits 📜🌟

  This project is licensed under the [MIT License](https://github.com/levvvy/esphome-lilygo-t-display-s3/blob/main/LICENSE).



# Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser.

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>

<script type="module" src="https://unpkg.com/esp-web-tools@9.1.0/dist/web/install-button.js?module"></script>
