# EEE3088F_Group17_Micromouse-Project
Designing a micromouse

## Project Overview

Welcome to the Micro-Mouse project for the year 2024! This project involves building subassemblies for your very own simplified micro-mouse, a maze-solving robot. While your micro-mouse may not match the speed of those featured in popular videos, this project serves as an exciting opportunity to delve into hardware design and some minor software components. Let's get started!

### Modules Description

#### 1. The Motherboard

- **Description**: The motherboard serves as the base board connecting all other PCBs together.
- **Interface Description**: 
  - Processor board: Two 2x19 (2.54mm pin pitch) pin headers.
  - Motors: Two 2x1 (2.54mm pin pitch) pin headers.
  - Sensor board: 2x14 (2.54mm pin pitch) pin headers.
  - Power board: 2x8 (2.54mm pin pitch) pin headers.

#### 2. The Processor

- **Description**: The processor board features an STM32L476 microcontroller.
- **Interface**: Detailed pinouts are provided for connections.

#### 3. Power Module

- **Description**: Responsible for powering the entire system and charging the battery.
- **Requirements**:
  - Operate 2 motors within specified parameters.
  - Provide analog connection for battery voltage monitoring.
  - Charge the battery from the 5V input pin.
  - Include an ON/OFF switch.

#### 4. Sensor Module

- **Description**: Responsible for detecting/sensing objects in the micro-mouse's path.
- **Requirements**:
  - Detect obstacles in front and possibly on the sides.
  - Design for reliability and power efficiency.
  - Interface with the processor to indicate sensed obstacles.

## Project Description

### Overview

- You will work in groups, with each member assigned to design either the power or sensing subsystem.
- Individual assessments will be conducted, and marks will be awarded accordingly.

### Subsystem Specifications

Detailed specifications and requirements for each subsystem are provided, including pinouts, connector types, power requirements, and considerations for design and functionality.

## Resources

- [Veritasium Video](https://www.youtube.com/watch?v=JnkMyfQ5YfY) - Watch this video to understand the concept of a micro-mouse.
- Additional resources and documentation are provided within the project repository.

## Conclusion

This README provides an overview of the Micro-Mouse project for 2024, outlining the objectives, module descriptions, and project requirements. Each subsystem has specific tasks and considerations to ensure successful integration into the micro-mouse design. For further details, refer to the project documentation and resources provided. Happy building!
```
