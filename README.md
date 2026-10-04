# ATmega128 Embedded Systems Projects

A collection of AVR Assembly projects developed for the **ATmega128 microcontroller**, progressing from basic arithmetic and I/O programming to timers, interrupts, pedestrian-crossing logic, 7-segment displays, and LCD interfacing.

## Projects

### Project 1 – 6-Bit Calculator

An AVR Assembly calculator that performs:

- Addition
- Subtraction
- Multiplication
- Division
- Error handling

Inputs are read from ATmega128 ports and results are stored in SRAM.

### Project 2 – 3-Way Traffic Light Controller

A traffic-control system for WEST, EAST, and NORTH routes.

Features:

- Timer-based traffic sequencing
- External interrupts
- Pedestrian crossing
- 7-segment countdown
- GPIO control
- Proteus simulation

When a pedestrian request occurs, NORTH traffic stops and the 7-segment display counts down from 9 to 0.

### Project 3 – Traffic Light Controller with LCD

An extended version of Project 2 with a **16×2 LCD** displaying the current traffic state.

Example:

```text
WEST/EAST GO
NORTH1/2 STOP
```

The final system combines:

- AVR timers
- External interrupts
- Traffic light control
- Pedestrian crossing
- 7-segment display
- LCD interfacing

## Repository Structure

```text
atmega128-embedded-projects/
├── project-1-calculator/
├── project-2-traffic-light/
├── project-3-traffic-light-lcd/
├── README.md
└── .gitignore
```

## Technologies

- AVR Assembly
- ATmega128
- Microchip / Atmel Studio
- Proteus Professional

## Key Concepts

- GPIO
- AVR registers
- SRAM
- Arithmetic operations
- Timers
- Interrupt Service Routines
- External interrupts
- 7-segment displays
- LCD interfacing

## Academic Context

Developed as part of:

**CNG336 – Introduction to Embedded Systems Development / EEE347 – Introduction to Microprocessors**

METU Northern Cyprus Campus.

## Contributors

- Furkan Sağlam
- Fatih Sağlam