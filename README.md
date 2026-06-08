# STM32-ESP32-UART-counter
UART communication between stm32 and esp32 using UART protocol.

STM32-ESP32-UART-Communication

Overview

This project demonstrates UART communication between an STM32F103 microcontroller and an ESP32 DevKit V1.

The STM32 acts as the transmitter and sends incrementing counter values every second through UART. The ESP32 receives the data and displays it on the Arduino Serial Monitor.

Hardware Used

- STM32F103 Development Board
- ESP32 DevKit V1
- ST-Link V2
- Jumper Wires
- Laptop

Software Used

- STM32CubeIDE 1.19.0
- Arduino IDE
- STM32 HAL Drivers

Wiring

STM32| ESP32
PA9 (TX)| GPIO16 (RX2)
GND| GND

Working

1. STM32 transmits counter values through UART1.
2. ESP32 receives the UART data through RX2 (GPIO16).
3. Received data is displayed on the Serial Monitor.

Example Output:

STM32 Counter: 0

STM32 Counter: 1

STM32 Counter: 2

STM32 Counter: 3










See the Images folder for setup photographs and output screenshots.
