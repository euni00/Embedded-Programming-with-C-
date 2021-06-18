# Embedded-Programming-with-C-

## Fundamentals of Embedded Systems

Embedded systems -> Computer systems combine hardware and software components -> Solving a specific task within a larger system or device.

microcontroller : Embedded system with a processor / firmware : its own software

A major part of an embedded program

1. Checking the status

2. Reading input

3. Sending data

4. Controlling the external device

### How are they different from desktop or web application?

Embedded system -> Do not have a user interface(Common) 

Finally, development, debugging, and diagnostics much more difficult campared to doing the same on traditional desktop or web applications.

### Types of embedded systems

Powerful systems -> Used for autonomous driving

large-scale storage systems -> Controling light bulbs or LED displays

1. Microcontrollers (MCUs)

2. A System on Chip (Soc)

3. Application-Specific Intergrated Circuits (ASICs)

4. Field Programmable Gate Arrays (FPGAs)

### 1. Microcontrollers

MCUs -> General-purpose integrated circuits designed for embedded applications

MCU chip -> Containing CPUs, momory, programmable input/output peripherals 

Uses of MCU -> Automobile engine control systems, medical devices, remote control etc ...

### 2. System on Chip

SoC -> Intergrated circuit combines all the electronic circuits and parts needed to solve a particular class of problem on a single chip.

Major benefits of SoC : miniaturization & low power consumption, less power

Uses of SoC : automotive industry, in wearable electronics, IoT, Raspberry Pi 

### 3. Application-specific intergrated circuits

ASICs -> Intergrated circuits customized by their manufactures for a particular use 

Cutomization -> Expensive process -> But meet the requirements that are often infeasible for solutions based on general-purpose hardware.

### 4. Field programmable gate arrays

FPGAs -> Semiconductor devices can be reprogrammed on a hardware level after manufacturing.

### Working with limited resources

High-end storage system -> utilizing large amounts of memory and resources for data caching, replication, encryption.

Embedded system hardware -> Designed to minimize the cost of the overall system. 

resources are scarce.

### Looking at performance implications

To Achieve maximum preformance -> Embedded programs utilize all the performance optimization capabilities of compilers.

### Working with different architectures

Have to know the traits of particular architectures, such as **endianness** and **alignment**

### Endianness 

Endianness defines the order in which bytes that represent large numerical values are stored in mermory. (큰 숫자 값을 나타내는 바이트가 mermory에 저장되는 순서를 정의)

Big-endian -> The most significant byte is stored first.

Little-endian -> The least significant byte is stored first.

### Alignment











