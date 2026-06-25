# IoT-Multi-Spectrum-Environmental-Control-Hardware
Self-Employed / Freelance
<img width="1600" height="1227" alt="Image" src="https://github.com/user-attachments/assets/2c805dcd-da11-4f27-9f0f-ddf06a9d8a62" />

IoT environmental control hardware system with Raspberry Pi Zero 2W carrier board, multi-spectrum UV/white/NIR LED board, sensors, load-cell input, fan control, battery charging, and power monitoring.


# IoT Multi-Spectrum Environmental Control Hardware

Two-board hardware system designed for IoT-connected environmental control and multi-spectrum light management. The system consists of a Main Control Board and a linked LED Board. The Main Board handles power regulation, sensing, connectivity, control signals, and system I/O, while the LED Board provides controlled multi-spectrum light output using white, UV, and high-power COB LED channels.

The Main Board is designed around a Raspberry Pi Zero 2W carrier-style architecture and includes connectors and circuitry for battery input, charging, fan control, reed-switch input, pushbutton input, buzzer output, load-cell measurement, current monitoring, temperature/humidity sensing, and external LED-board control. The PCB labels and BOM show support for Raspberry Pi Zero 2W, fan, reed switch, buzzer, load cell, charging input, INA219 current monitoring, HX711 load-cell interface, SHT41 temperature/humidity sensing, PCA9685 PWM control, IXDD604 gate drivers, and boost/power-conversion stages.

The LED Board acts as the light engine of the system. It includes arrays of white LEDs, UV-365nm LEDs, UV-400nm LEDs, COB-UV, COB-White channels, MOSFET switching, a local SHT temperature sensor, and JST interconnects to the Main Board. This allows the main controller to drive different light channels and monitor local LED-board temperature.

Together, both boards form a modular hardware platform for controlled lighting, environmental sensing, and IoT-based monitoring applications. The design is suitable as a prototype hardware platform for experimental chambers, controlled illumination systems, environmental test setups, or smart sensing/lighting nodes.



## Key Features

- Two-board modular hardware architecture
- Raspberry Pi Zero 2W carrier-style Main Board
- Dedicated multi-spectrum LED Board
- White LED, UV-365nm, UV-400nm, COB-UV, and COB-White channels
- NIR connector/interface support on Main Board
- PCA9685-based PWM expansion
- IXDD604 gate-driver based LED switching
- Temperature and humidity sensing using SHT41
- Load-cell measurement using HX711
- Current monitoring using INA219
- Battery input and USB-C charging interface
- Fan control, buzzer output, pushbutton input, and reed-switch input
- Boost and regulation stages for system and LED power
- JST/header-based interconnection between Main Board and LED Board



## Main Board

The Main Board acts as the control, sensing, and power-management hub of the system. It provides the Raspberry Pi Zero 2W interface, power regulation, battery charging, LED-control signal generation, sensing interfaces, user inputs, and auxiliary outputs.

Main Board functions include:

- Raspberry Pi Zero 2W interface
- Battery input and USB-C charging
- Boost/regulation stages for system and LED power
- PCA9685 PWM control
- IXDD604 gate-driver interface
- SHT41 temperature/humidity sensing
- HX711 load-cell measurement
- INA219 current monitoring
- Fan, buzzer, pushbutton, and reed-switch interfaces
- Output connectors for LED/NIR/light-control channels

<img width="747" height="682" alt="Image" src="https://github.com/user-attachments/assets/a7142b12-712a-435d-bbf4-9665cc1186fc" />
<img width="796" height="642" alt="Image" src="https://github.com/user-attachments/assets/4f1a5aa3-820b-4e29-b5f6-c89eaf9f27ef" />



## LED Board

The LED Board is the dedicated light-output board connected to the Main Board through JST/header connections. It contains multiple LED channels and switching circuitry for controlled multi-spectrum illumination.

LED Board functions include:

- White LED array
- UV-365nm LED array
- UV-400nm LED array
- COB-UV channel
- COB-White channel
- MOSFET-based channel switching
- Local SHT temperature sensor
- JST interconnects for power, control, and sensor signals


##  Summary

Designed a two-board IoT-connected environmental control hardware system consisting of a Raspberry Pi Zero 2W-based Main Control Board and a linked multi-spectrum LED Board. The Main Board handles power regulation, battery charging, PWM control, gate driving, sensing, load-cell measurement, fan/buzzer/reed-switch I/O, and current monitoring. The LED Board provides controlled white, UV-365nm, UV-400nm, COB-UV, and COB-White light channels with MOSFET switching and local temperature sensing.

<img width="711" height="675" alt="Image" src="https://github.com/user-attachments/assets/376bc79f-1c93-4595-a8fd-d866b4157272" />

<img width="902" height="792" alt="Image" src="https://github.com/user-attachments/assets/7ab96799-d297-4232-988a-cb2dec79e3f6" />
