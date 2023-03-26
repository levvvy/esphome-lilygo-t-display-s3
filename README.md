# Lilygo T-Display-S3 ESPHome Implementation

[![GitHub release](https://img.shields.io/github/release/levvvy/esphome-lilygo-t-display-s3.svg)](https://github.com/levvvy/esphome-lilygo-t-display-s3/releases)
[![GitHub issues](https://img.shields.io/github/issues/levvvy/esphome-lilygo-t-display-s3.svg)](https://github.com/levvvy/esphome-lilygo-t-display-s3/issues)
[![License](https://img.shields.io/github/license/levvvy/esphome-lilygo-t-display-s3)](https://github.com/levvvy/esphome-lilygo-t-display-s3/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/levvvy/esphome-lilygo-t-display-s3.svg)](https://github.com/levvvy/esphome-lilygo-t-display-s3/stargazers)

This repository provides an implementation of Lilygo T-Display-S3 with ESPHome, allowing you to integrate the display module into your ESPHome projects easily. The **Lilygo T-Display-S3** is a compact and versatile development board with an integrated display, perfect for various IoT and home automation applications.

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

  ## Software Setup 💾

  1. Install ESPHome on your computer following the official documentation: [Getting Started with ESPHome](https://esphome.io/guides/getting_started_command_line.html)

  2. Clone this repository to your local machine:
     ```
     git clone https://github.com/levvvy/esphome-lilygo-t-display-s3.git
     ```

  3. Change into the `esphome-lilygo-t-display-s3` directory and create a new file called `secrets.yaml`. Add your Wi-Fi credentials and other sensitive information to this file. Example:
     ```
     wifi_ssid: "your_wifi_ssid"
     wifi_password: "your_wifi_password"
     ```

  4. Edit the `esphome-lilygo-t-display-s3.yaml` file to configure the display layout, themes, and any additional sensors or peripherals you want to use. Check the comments in the file for guidance.

  5. Compile and upload the ESPHome firmware to your Lilygo T-Display-S3 board. You can use the following command, replacing `<your-device-name>` with a unique name for your device:
     ```
     esphome run -d <your-device-name> lilygo_t_display_s3.yaml
     ```

  6. (Optional) If you use Home Assistant, the board should now appear in the Integrations menu. Follow the instructions to add it to your Home Assistant instance.

  7. Your Lilygo T-Display-S3 should now be running the ESPHome firmware and displaying the configured information on the screen. Enjoy your new IoT display!

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

</details>

