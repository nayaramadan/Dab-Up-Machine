# Dapper Tracker - How Well Can You Offer a ***Low Five?***
> Made For Hack Club's Outpost Hackathon and presented at Open Sauce 2026

The Dapper Tracker is a 1DOF Robotic Arm with an IMU inside the palm of the hand which detects how hard someone gives it a handshake. A score is given from 0-100. A bad score means too hard or too soft of a handshake, aim for the right pressure. 

BOM
# Bill of Materials

| # | Component | Qty | Notes |
|---|-----------|-----|-------|
| 1 | USB-C PD trigger board (set to 9V) | 1 | Main power source |
| 2 | LM2596 buck converter (adjustable) | 2 | One set to 5.0V (logic), one set to 6.0V (servo/LED) |
| 3 | Seeed XIAO RP2040 | 1 | Main microcontroller |
| 4 | A4988 stepper driver | 1 | |
| 5 | NEMA17 stepper motor | 1 | 4-wire (black/green/red/blue) |
| 6 | MG996R servo | 1 | |
| 7 | BMI160 IMU breakout | 1 | Accel + gyro, I2C |
| 9 | Push button | 1 | Momentary, breadboard-friendly |
| 10 | CYD (ESP32 display board) | 1 | Powered/driven entirely over its own USB to laptop — not on the power rails |
| 11 | 330Ω resistor | 1 | In series with LED `DIN` signal line |
| 12 | 100µF electrolytic capacitor | 1 | Across A4988 `VMOT`/`GND` |
| 13 | 1000µF electrolytic capacitor | 2 | One across servo `red`/`brown`, one across LED `V+`/`GND` |
| 14 | Breadboard | 1–2 | A second one helps if separate rail strips for 5V/6V run out |
| 15 | Jumper wires (M-M, M-F) | assorted | Rails, signal lines, grounds |
| 16 | USB-C cable | 1 | XIAO RP2040 to laptop |
| 17 | USB cable (for CYD) | 1 | CYD to laptop — check connector type (often micro-USB or USB-C) |


<img src="IMG_1695.jpg" alt="Project Screenshot" width="500">

