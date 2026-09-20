# ESP8266 Wi-Fi Security Research Project

A hardware-based Wi-Fi security research project built around the **ESP8266** platform. The project explores wireless network discovery, access-point and station information, device management, and security-testing concepts through an embedded web interface.

> **Educational & Authorized Testing Only:** This project is intended for cybersecurity education, controlled laboratory environments, and testing networks/devices that you own or have explicit permission to assess. Do not use it to disrupt, interfere with, or access networks without authorization.

## Features

* Wi-Fi network discovery and scanning
* Access-point information display
* Connected-station information
* Embedded web-based interface
* Device configuration and settings
* ESP8266-based standalone operation
* Hardware status and LED handling
* Multiple source modules for scanning, UI, Wi-Fi management, and configuration
* Designed for wireless-security research and experimentation

## Hardware

The project is designed around an **ESP8266 development board**.

### Recommended Components

* ESP8266 development board
* USB cable for programming and power
* Optional display/interface hardware depending on the project configuration
* Optional LEDs or indicators

## Software

### Main Technologies

* **ESP8266**
* **Arduino C/C++**
* **Arduino IDE / compatible ESP8266 development environment**
* Embedded web interface
* Wi-Fi networking APIs

## Project Structure

| File / Module                       | Purpose                                  |
| ----------------------------------- | ---------------------------------------- |
| `esp8266_deauther.ino`              | Main Arduino entry point                 |
| `Scan.cpp / Scan.h`                 | Wireless scanning functionality          |
| `Accesspoints.cpp / Accesspoints.h` | Access-point management                  |
| `Stations.cpp / Stations.h`         | Station/device management                |
| `wifi.cpp / wifi.h`                 | Wi-Fi-related functionality              |
| `DisplayUI.cpp / DisplayUI.h`       | User-interface and display functionality |
| `CLI.cpp / CLI.h`                   | Command-line/interface functionality     |
| `settings.cpp / settings.h`         | Configuration and settings               |
| `SSIDs.cpp / SSIDs.h`               | SSID-related data management             |
| `Names.cpp / Names.h`               | Name/device information handling         |
| `led.cpp / led.h`                   | LED/status handling                      |
| `EEPROMHelper.h`                    | Persistent configuration storage         |
| `functions.h`                       | Shared project functions                 |
| `language.h`                        | Interface language resources             |
| `oui.h`                             | Hardware/vendor identification data      |
| `webfiles.h`                        | Embedded web-interface resources         |

## How It Works

The ESP8266 provides the wireless interface and embedded processing required by the project.

At a high level, the system can:

1. Initialize the ESP8266 hardware and software components.
2. Discover nearby wireless networks.
3. Collect available network and device information.
4. Present information through the device's interface.
5. Allow authorized security-testing functionality to be controlled through the configured interface.
6. Store selected configuration information for later use.

## Security Research Applications

This project can be used as a learning platform for understanding:

* IEEE 802.11 wireless networking concepts
* Wireless network discovery
* Access-point and station relationships
* Embedded networking
* ESP8266 programming
* Wireless security assessment concepts
* Web interfaces on embedded devices
* Network-security monitoring and experimentation

## Responsible Use

Wireless security tools can affect devices and networks outside the intended test environment.

Use this project only when you have explicit authorization.

**Do not:**

* Disrupt networks you do not own.
* Target other people's devices.
* Interfere with public, enterprise, campus, or residential networks without permission.
* Use the project to bypass access controls or interfere with communications.

For experimentation, use a dedicated lab network and devices that you control.

## Learning Objectives

This project is useful for students and security researchers who want practical experience with:

* Embedded C/C++
* ESP8266 architecture
* Wi-Fi protocols
* Wireless security concepts
* Network discovery
* Embedded web applications
* Hardware/software integration

## License

See the [`LICENSE`](LICENSE) file included in this repository for the applicable license and terms.

## Disclaimer

The authors and contributors are not responsible for misuse of this software or for damage caused by unauthorized use.

This repository is intended for **educational cybersecurity research and authorized security testing**.
