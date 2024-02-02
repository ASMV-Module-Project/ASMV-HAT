# ASMV-HAT :tophat: HAT (add-on board) for the ASMV Module
> :zap: Expanding Connectivity for drones & robots

<img src="https://github.com/ASMV-Module-Project/ASMV-HAT/assets/24481026/ac358355-1894-456a-89cd-086071c7de7a" alt="HAT-ASMV-Logo-V1.0-20240201" width="30%"/>

## :page_with_curl: Licence
We use the [Hardware Source Licence V1.0](https://github.com/Hardware-Source-Licence/HSL-V1.0), which offers transparent access to our designs and promotes free use for research, development, private & community projects, with certain conditions for commercial usage.

## :raising_hand: Contributing
To contribute or inquire, please engage in our [Forum](https://github.com/orgs/ASMV-Module-Project/discussions) or email us at MermozRAL.Association@gmail.com.

## :robot: Key Features of the ASMV-HAT

### :electric_plug: Enhanced Connectivity Suite
- **GPIO Compatibility**: Fully compatible with Raspberry Pi Zero 2 W's GPIO, enabling extensive functionality for diverse applications.
  
- **Versatile Interface Options**: Equipped with a range of connectors, the HAT is designed for high-speed and precision applications in robotics and drones.

### :gear: Connector Specifications

| Connector   | Detail                                       | Voltage | Connector Type | Signal Type | Max. Speed           |
|-------------|----------------------------------------------|---------|----------------|---------------|--------------------|
| USB-OTG     | USB port of the RpiZ (OTG)                   | 5V      | JST-GH-6       | USB           | Data Only 480 Mbps |
| USB-Power   | Power In USB Port                            | 5V      | USB-Micro      | DC Power Only | -                  |
| UART-H      | Hardware High-Speed UART                     | 3.3V    | JST-GH-6       | TTL           | 115200bps, 256000bps |
| UART-S      | Software Slow Speed UART (9600 Baud max)     | 3.3V    | JST-GH-6       | TTL           | 9600bps            |
| I2C-H       | I2C Hardware – Used by the RTC               | 3.3V    | JST-GH-4       | I2C           | up to 400 kHz      |
| I2C-S       | I2C Software (gpiod) – Sonars & Sensors      | 3.3V    | JST-GH-4       | I2C           | up to 200 kHz      |
| POWER IN    | External power supply – 6 to 60 V to 5V 2A   | 5V      | JST-RCY        | DC Power Only | @2A max            |
| UART-B      | UART-B / TTL - from CP2102 IC                | 3.3V    | JST-GH-6       | TTL           | Up to 256000bps    |
| RTC         | Real Time Clock -  DS3231                    | 3.3V    | Dupont         | I2C           | -    |

The ASMV-HAT is the cornerstone of your innovative projects, bridging the gap between idea and reality with its robust capabilities and adaptability.






