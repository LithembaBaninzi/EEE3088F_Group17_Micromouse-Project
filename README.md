# EEE3088F_Group17_Micromouse-Project
Designing a micromouse

## Project Overview

Welcome to the Micro-Mouse project for the year 2024! This project involves building subassemblies for your very own simplified micro-mouse, a maze-solving robot. While your micro-mouse may not match the speed of those featured in popular videos, this project serves as an exciting opportunity to delve into hardware design and some minor software components. Let's get started!

![image](https://github.com/LithembaBaninzi/EEE3088F_Group17_Micromouse-Project/assets/160032740/a1bedfed-049d-4eec-bc05-01428b759e61)

### Subsystem Specifications

Detailed specifications and requirements for each subsystem are provided, including pinouts, connector types, power requirements, and considerations for design and functionality.


### Modules Description

#### 1. The Motherboard

- **Description**: The motherboard serves as the base board connecting all other PCBs together.
- **Interface Description**: 
  - Processor board: Two 2x19 (2.54mm pin pitch) pin headers.
  - Motors: Two 2x1 (2.54mm pin pitch) pin headers.
  - Sensor board: 2x14 (2.54mm pin pitch) pin headers.
  - Power board: 2x8 (2.54mm pin pitch) pin headers.

![image](https://github.com/LithembaBaninzi/EEE3088F_Group17_Micromouse-Project/assets/160032740/f364a601-29ec-446f-9347-6f49f21be087)

#### 2. The Processor

- **Description**: The processor board features an STM32L476 microcontroller.
- **Interface**: Detailed pinouts are provided for connections.

![image](https://github.com/LithembaBaninzi/EEE3088F_Group17_Micromouse-Project/assets/160032740/739b12cd-66b0-4dd0-b219-8a5c74271aff)

#### 3. Power Module

- **Description**: Responsible for powering the entire system and charging the battery.
- **Requirements**:
  - Operate 2 motors within specified parameters.
  - Provide analog connection for battery voltage monitoring.
  - Charge the battery from the 5V input pin.
  - Include an ON/OFF switch.

![image](https://github.com/LithembaBaninzi/EEE3088F_Group17_Micromouse-Project/assets/160032740/ef25912a-1cad-42b1-8840-e74d401e6da1)

#### 4. Sensor Module

- **Description**: Responsible for detecting/sensing objects in the micro-mouse's path.
- **Requirements**:
  - Detect obstacles in front and possibly on the sides.
  - Design for reliability and power efficiency.
  - Interface with the processor to indicate sensed obstacles.

![image](https://github.com/LithembaBaninzi/EEE3088F_Group17_Micromouse-Project/assets/160032740/ccd93241-cb0e-4c8e-97a0-0ce8243440be)

#### The maze
The maze will have dead ends, multiple paths to the finishing area with each pixel being a 200mm square.
There are multiple paths to get to the goal.
An example is provided below:


![image](https://github.com/LithembaBaninzi/EEE3088F_Group17_Micromouse-Project/assets/160032740/0930c01e-27d8-413d-9ee6-9d302549a6f8)


## Resources

- [Veritasium Video](https://www.youtube.com/watch?v=JnkMyfQ5YfY) - Watch this video to understand the concept of a micro-mouse.
- Additional resources and documentation are provided within the project repository.

## Conclusion

This README provides an overview of the Micro-Mouse project for 2024, outlining the objectives, module descriptions, and project requirements. Each subsystem has specific tasks and considerations to ensure successful integration into the micro-mouse design. For further details, refer to the project documentation and resources provided. Happy building!
```
