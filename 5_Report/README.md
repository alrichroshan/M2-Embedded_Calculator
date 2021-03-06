# Report

# Introduction
A Calculator is a device which can perform some mathematical operations. In this project, a calculator on ATmega328p using LCD and Keypad is developed which will perform calculations depending on the input from the user.

# Components Used
1. ATmega328p microcontroller.
2. 16x2 LCD
3. 4x4 Keypad

# Software Used
1. SimulIDE
2. Visual Studio

# Cost and Features
Depending upon the project how well it is built and all the requirements will meet the cost and it can be varied according to the market.
1. Addition
2. Subtraction
3. Multiplication
4. Division

# SWOT Analysis
## Strengths
1. Cost Advantage.
2. It can perform all arithmetic calculation.

## Weakness
1. Competition.

## Opportunities
1. Advanced Tech Capabilities.
2. No Creative Limits.

## Threats
1. Advanced featured calculators are already in the market.
2. Decreasing Market Demand

# 4W's and 1 H's
## Why:
1. To reduce the complexity of calculations.
2. It can be used by anyone at any place.

## Where:
1. This can be used in our daily lives.
2. We can use it in the banking system for calculation.

## Who:
1. Can be used as a reference for advanced calculators.

## When:
1. One can calculate from anywhere.
2. The project can be used when the calculations are required and the result will be obtained fastly.

## How:
1. By giving different inputs one can find their desired output.
2. It will be helpful in performing various calculations. This will give accurate results.

# High Level Requirements
| ID | Description | Status |
|---|---|---|
| HLR_1 | Microcontroller | Implemented |
| HLR_2 | Display | Implemented |
| HLR_3 | Keypad | Implemented |
| HLR_4 | Software | Implemented |

# Low Level Requirements
| ID | Description | Status |
|---|---|---|
| LLR_1 | ATmega328 | Implemented |
| LLR_2 | LCD | Implemented |
| LLR_3 | 4x4 Keypad | Implemented |
| LLR_4 | Visual Studio & SimulIDE | Implemented |

# Design

# Behavior Diagram
![Behavior Diagram](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Behavior%20Diagram.png)

# Structure Diagram
![Structure Diagram](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Structure%20Diagram.png)

# Block Diagram
![Block Diagram](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Block%20Diagram.png)

# Simulation
![Simulation](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Simulation.png)

# Simulation
The calculator is implemented in Embedded C program and the working is demonstrated using SimulIDE software.

# Functions
1. When the C button is pressed the calculator power on.
2. It can perform Addition, Subtraction, Multiplication, Division.

## Addition
Calculator performing addition operation.

![Addition](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Addition.png)

## Subtraction
Calculator performing subtraction operation.

![Subtraction](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Subtraction.png)

## Multiplication
Calculator performing multiplication operation.

![Multiplication](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Multiplication.png)

## Division
Calculator performing division operation.

![Division](https://github.com/alrichroshan/M2-Embedded_Calculator/blob/main/6_Images/Division.png)

# Test Plan

# High Level Test Plan
| ID | Description | Expected I/P | Expected O/P | Actual O/P | Type Of Test |
|---|---|---|---|---|---|
| HLTP_1 | Switch On | High | The Program Should Start | SUCCESS | Requirement Based |
| HLTP_2 | Taking Input From The User | Value Input | Should Give Output To The User | SUCCESS | Scenario Based |
| HLTP_3 | Giving Output From The Input | Value Input From The User | Displays Output | SUCCESS | Boundary Based |

# Low Level Test Plan
| ID | Description | Expected I/P | Expected O/P | Actual O/P | Type Of Test |
|---|---|---|---|---|---|
| LLTP_1 | Performing Arthmetic operation '+' | (600, 100) | 700 | 700 | Requirement Based |
| LLTP_2 | Performing Arthmetic operation '-' | (800, 100) | 700 | 700 | Requirement Based |
| LLTP_3 | Performing Arthmetic operation '*' | (10, 7) | 70 | 70 | Requirement Based |
| LLTP_4 | Performing Arthmetic operation '/' | (10, 2) | 5 | 5 | Requirement Based |