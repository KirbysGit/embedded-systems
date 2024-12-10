# Embedded Systems (EEL 4742C)

## Overview

Welcome to my **Embedded Systems (EEL 4742C)** repository! This repository contains lab assignments and projects that demonstrate practical applications of embedded systems concepts using the Texas Instruments MSP430 microcontroller and BoosterPack MKII. Each file showcases programming techniques for real-time embedded applications, including handling interrupts, timers, communication protocols, and interfacing with peripherals.

---

## Course Topics

- **Introduction to Embedded Systems**
- MSP430 Microcontrollers and Programming Environment
- Masking Arithmetic (Bit Manipulations)
- Using Timers and Advanced Timer Features
- Interrupt Programming and Low-Power Modes
- LCD and Pixel Displays
- UART, I2C, and SPI Communication Protocols
- Analog-to-Digital Conversion (ADC)
- Concurrent Event Handling
- Push Button Debouncing Algorithms

---

## Learning Outcomes

By the end of the course, I achieved the following:
1. Developed proficiency in embedded systems programming.
2. Mastered masking arithmetic for bit-level manipulations.
3. Designed timer-based applications with various modes and channels.
4. Implemented and debugged interrupt-driven programs.
5. Utilized low-power modes effectively in embedded applications.
6. Interfaced with segmented LCD displays and programmed pixel graphics.
7. Handled SPI, I2C, and UART communication protocols.
8. Used ADC modules for real-time sensor data acquisition.
9. Designed debounce algorithms for reliable push button operations.

---

## Repository Contents

| File Name                    | Description                                                                                     | Topic Covered                  |
|------------------------------|-------------------------------------------------------------------------------------------------|--------------------------------|
| `1.3LEDinSync.txt`           | Implements synchronous flashing of LEDs using masking arithmetic and timers.                   | Masking Arithmetic, Timers     |
| `1.4_2ndSolution.txt`        | Alternate implementation of LED synchronization.                                               | Masking Arithmetic             |
| `1.4_3rdSolution.txt`        | Further optimized solution for LED synchronization.                                            | Masking Arithmetic             |
| `1.51st_Solution.txt`        | Initial solution for a basic timing problem.                                                   | Timer Usage                    |
| `1.52nd_Solution.txt`        | Refined timing solution with improved efficiency.                                              | Timer Usage                    |
| `10.1MultipleChannels.txt`   | Configures timers with multiple channels for advanced timing applications.                     | Advanced Timer Features        |
| `10.2ThreeChannels.txt`      | Demonstrates timer usage with three separate channels.                                         | Advanced Timer Features        |
| `10.3PWM.txt`                | Generates pulse-width modulation (PWM) signals.                                               | PWM Generation                 |
| `10.4TimerInput.txt`         | Handles timer input events for real-time systems.                                              | Timers                         |
| `11.1HVAC.txt`               | Simulates HVAC system control using real-time inputs.                                          | Concurrent Event Handling      |
| `11.2ExtraDelay.txt`         | Adds and manages extra delay for signal processing.                                            | Timers                         |
| `11.3Debounce.txt`           | Implements debounce algorithms for push buttons.                                               | Push Button Debouncing         |
| `2,2TwoButtoms.txt`          | Reads inputs from two push buttons with debouncing.                                            | Push Button Debouncing         |
| `2.1PushButtons.txt`         | Reads push button inputs.                                                                      | Push Button Input Handling     |
| `2.3ElectricGenerator.txt`   | Simulates a basic electric generator circuit.                                                  | Timers                         |
| `2.4ElectricGeneratorV2.txt` | Enhanced version of the electric generator simulation.                                         | Timers                         |
| `3,2UpMode.txt`              | Demonstrates "Up Mode" operation for timers.                                                   | Timers                         |
| `3,3SignalRepeater.txt`      | Repeats signal transmission with real-time processing.                                         | Timers                         |
| `3.1FlashingLED.txt`         | Flashes LEDs at regular intervals.                                                             | Timers                         |
| `4.1Interrupt.txt`           | Demonstrates the use of interrupts to toggle LEDs.                                             | Interrupts                     |
| `4.2UPMode.txt`              | Configures timers for "Up Mode" with interrupt handling.                                       | Interrupts, Timers             |
| `4.3PushButtonWInterrupt.txt`| Reads push button inputs using interrupts.                                                     | Interrupts                     |
| `4.4LPM.txt`                 | Utilizes low-power modes for energy efficiency.                                                | Low-Power Modes                |
| `4.5CrawlerGuidanceSys.txt`  | Simulates a guidance system for a crawler.                                                     | Interrupts, Timers             |
| `5.1PrintLCDDisplay.txt`     | Displays text on the segmented LCD display.                                                   | LCD Programming                |
| `5.2CounterDisplay.txt`      | Displays a counter on the LCD display.                                                        | LCD Programming                |
| `6.1UARTTransfer.txt`        | Transfers data over UART communication.                                                       | UART Communication             |
| `6.216bit.txt`               | Handles 16-bit data transfer over UART.                                                       | UART Communication             |
| `6.3ModifyUART.txt`          | Modifies UART communication parameters.                                                       | UART Communication             |
| `7.1I2CTransmission.txt`     | Transmits data over the I2C protocol.                                                         | I2C Communication              |
| `7.2LUX.txt`                 | Reads and transmits LUX sensor data.                                                          | I2C Communication              |
| `8.1UsingADC.txt`            | Captures analog input using the ADC module and converts it to digital output.                  | Analog-to-Digital Conversion   |
| `8.2XandY.txt`               | Processes X and Y coordinates from an input device using ADC.                                  | Analog-to-Digital Conversion   |
| `9.1TwoFuncs.txt`            | Implements two functions to manage concurrent system behavior.                                 | Concurrent Event Handling      |
| `9.2ThePark.txt`             | Simulates a parking lot management system.                                                    | Concurrent Event Handling      |
| `9.3OpticalSensor.txt`       | Interfaces with an optical sensor for real-time data acquisition.                              | ADC, Sensors                   |

---
