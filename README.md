# Harel-MCU-Board-PCB-Design-Final-Project-
MCU control Board based on STM32F405RGT6(4 Layers Layout) , including USB-C, INA186 current sensor, SPI/UART communication, and an expansion connector for an RF card.

The board was designed and developed as a custom MCU control board  to interface with a PLL-based Signal Generator board(Part 2 of the final project) ,  
while also i tried make it   versatile enough to serve as a  development platform for my  future projects and testing prototypes.


The MCU board includes:

- **Power Input:**  
  The board can be powered either through a **USB Type-C connector (5 V)**  
  or via an **external DC power supply**.  

- **Current Sensor (INA186):**  
  Integrated  current sensor for monitoring the total current  
  consumption of both the **MCU board and the external RF board** for the project .  

- **Microcontroller (STM32F405RGT6):**  
  - **Core Frequency:** 168 MHz (ARM Cortex-M4F)  
  - **Flash Memory:** 1 MB  
  - **SRAM:** 192 KB  
  - **GPIOs:** 63 configurable pins  
  - **Communication Interfaces:** 3× SPI  ,  3× UART  ,  2× I²C  ,  2× CAN  ,  1× USB 

- **Expansion & Output  Connectors:**  
  Standard output connectors are provided for  communication  
  with the **RF board** used in the final project.

- **Layout:**  

The board is designed as a **4-layer PCB** 1.6mm  with the following stack-up:  
**SIG+PWR – GND – POWER – SIG**, optimized for both signal integrity and  power distribution ( ground polygons and trace width calculation  .  
Most components are **SMD 0402 / 0603** , ensuring compact layout. 

During the design process, I focused on applying **proper PCB layout principles** used in professional board design:
- **Ground plane continuity:** maintained a  GND layer (L2) for stable reference and reduced EMI.   
- **Short return paths:** .  
- **Decoupling strategy:** 
- **Via stitching:**   
- **Controlled impedance routing:** 
This approach allowed me to gain hands-on experience with **real-world PCB design constraints**,  
including manufacturability (DFM), electrical performance, and mechanical layout alignment between  boards.
<img width="1357" height="875" alt="image" src="https://github.com/user-attachments/assets/a8e221be-8b17-48a1-a27b-afe8c41f549a" />
<img width="1073" height="710" alt="image" src="https://github.com/user-attachments/assets/6e4b6b99-dfa7-4e47-9418-c59f801dd3ff" />








