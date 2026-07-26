# Password Security System

## Overview

The Password Security System is a hardware-based authentication system designed to provide secure access without the use of a microcontroller. The system uses digital logic ICs, DIP switches, and a 555 timer to verify a predefined password. If the correct password is entered, access is granted. After three consecutive incorrect attempts, an alarm is activated to indicate unauthorized access.

The project demonstrates the implementation of digital logic circuits for access control while emphasizing simplicity, reliability, and low cost.

## Features

- Hardware-based password authentication
- No microcontroller or software programming required
- Password input using DIP switches
- Three-attempt security mechanism
- Automatic alarm activation after repeated incorrect attempts
- Seven-segment display for attempt indication
- Low-cost and reliable digital circuit design

## Hardware Components

- Logic ICs
- 555 Timer IC
- DIP Switches
- Seven Segment Display
- Buzzer
- LEDs
- Push Buttons
- Resistors
- Capacitors
- Breadboard
- Power Supply

## Software Used

- Proteus Design Suite
- Digital Circuit Simulation Tools

## Working Principle

The system stores a predefined password using digital logic circuits.

1. The user enters the password using the DIP switches.
2. The entered password is compared with the predefined password.
3. If the password matches, access is granted.
4. If the password is incorrect, the incorrect attempt counter increases.
5. After three incorrect attempts, the 555 timer activates the buzzer to indicate unauthorized access.
6. The system can then be reset for further operation.

## System Block Diagram

```
        User Input
       (DIP Switches)
              │
              ▼
      Password Comparator
              │
      ┌───────┴────────┐
      │                │
Correct Password   Incorrect Password
      │                │
      ▼                ▼
 Access Granted   Attempt Counter
                       │
              Three Failed Attempts
                       │
                       ▼
                 555 Timer Circuit
                       │
                       ▼
                     Buzzer
```

## Applications

- Door Access Systems
- Locker Security
- Laboratory Equipment Protection
- Office Security
- Educational Demonstrations
- Electronic Lock Systems

## Advantages

- Low-cost implementation
- Simple hardware design
- No software dependency
- Fast operation
- Reliable authentication
- Easy to understand and maintain

## Future Improvements

- Keypad-based password entry
- LCD display
- Fingerprint authentication
- RFID integration
- GSM alert system
- IoT-based remote monitoring
- OTP verification

## Repository Contents

- Project report
- Circuit diagrams
- Proteus simulation files
- Prototype images
- Hardware photographs

## Author

**J. Adwaith**

B.Tech in Electrical and Electronics Engineering

TKM College of Engineering

## License

This project is licensed under the MIT License.
