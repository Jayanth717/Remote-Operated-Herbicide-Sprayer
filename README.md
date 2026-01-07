### Remote Operated Herbicide Sprayer with Controlled Droplet Applicator
### Overview

This project presents the design and development of a remote-operated agricultural robot intended to safely and efficiently spray herbicides in palm plantations and similar agricultural environments. The system minimizes direct human exposure to toxic chemicals while enabling precise, controlled spraying in terrains where manual operation is difficult or unsafe.

The robot integrates mechanical design, embedded systems, and mobile application control, demonstrating a complete end-to-end mechatronic solution.

### Problem Statement
### Traditional herbicide spraying methods rely heavily on manual labor, often exposing farmers to:

Toxic chemicals

Extreme heat and humidity

Physical strain and health risks

### Additionally, manual spraying leads to:

Overuse of chemicals
Uneven spraying
Soil degradation

This project addresses these challenges by introducing a remote-controlled spraying robot that improves safety, precision, and efficiency.

### Solution Summary
The proposed system is a mobile robotic platform capable of:

Remote navigation using a smartphone

Precision herbicide spraying via a controlled droplet mechanism

Operating in uneven and rugged plantation terrains

Reducing chemical waste and human exposure

The robot is controlled using an Arduino Mega 2560, with commands sent through a Bluetooth-enabled Android application.

### System Architecture
The system consists of the following major modules:

### Mechanical Structure

3-layer chassis design

Supports batteries, electronics, tanks, and spraying manipulator

Designed for stability and load-bearing capability

### Control & Electronics

Arduino Mega 2560 as the main controller

Motor drivers (L298N), relays, pumps, and servo motors

HC-05 Bluetooth module for wireless control

### Spraying Mechanism

Multi-tank system (water, herbicide, mixing tank)

Servo-driven serial manipulator for directional spraying

Controlled droplet application via nozzle

### Mobile Application

Android app developed using MIT App Inventor

Controls robot movement, pump activation, and spray direction

### Key Features

Remote operation using smartphone

Precision spraying with controlled droplet size

Reduced chemical wastage

Improved safety for farmers

Modular and cost-effective design

Operates on rough and uneven terrains

### Testing & Validation

The system was validated through:

Breadboard testing of electronic circuits

Motor and pump testing under load

Manipulator and spraying tests using the mobile application

End-to-end functional testing after full assembly

The robot successfully demonstrated stable movement, accurate spraying, and reliable remote control.

### Technologies Used

Arduino Mega 2560

Embedded C / Arduino IDE

MIT App Inventor (Android)

Bluetooth (HC-05)

AutoCAD

DC Motors, Servo Motors, Pumps, Relays

### Cost & Feasibility

The complete prototype was built with a low-cost approach, making it feasible for real-world agricultural deployment. A detailed cost breakdown is available in the project report.

### Future Enhancements

Fully autonomous navigation using sensors

Integration of computer vision for targeted spraying

Voice control using speech recognition

Enhanced obstacle handling mechanisms

### Author

Jayanth Kumar

Mechatronics / Computer Science
