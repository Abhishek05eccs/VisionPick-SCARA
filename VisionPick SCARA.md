# VisionPick SCARA

### Smart Vision, Precise Motion

An AI-powered autonomous semiconductor wafer handling, inspection, and defect sorting system designed to automate wafer transfer and quality inspection using computer vision, precision SCARA robotics, embedded systems, and intelligent automation.

---

# About The Project

VisionPick SCARA is designed to address the challenges of semiconductor wafer handling, where manual operations can lead to contamination, scratches, alignment errors, and reduced manufacturing efficiency.

Semiconductor fabrication requires highly precise, repeatable, and contamination-free handling systems. Industrial wafer handling solutions are often expensive and inaccessible for educational, research, and prototype development purposes.

VisionPick SCARA provides a cost-effective intelligent automation platform that integrates machine vision, embedded control, precision robotics, and automated inspection into a single system.

The project consists of:

- Vision-Based Wafer Inspection System
- Autonomous SCARA Pick-and-Place Robot
- Intelligent Defect Sorting Mechanism

The system continuously detects wafers, analyzes their condition, performs autonomous pick-and-place operations, and sorts them based on inspection results.

---

# Why VisionPick SCARA?

Semiconductor wafer handling faces several challenges:

- Wafer contamination
- Surface scratches
- Alignment errors
- Human inspection limitations
- Reduced manufacturing efficiency
- High automation costs

Most available solutions focus on either robotic handling or inspection systems separately.

VisionPick SCARA addresses these challenges by combining:

- Vision-guided wafer detection
- Intelligent defect inspection
- Autonomous robotic handling
- Precision motion control
- Vacuum-based pick-and-place
- Automatic Good/Reject sorting

This creates a complete semiconductor automation platform capable of reducing human intervention while improving accuracy and productivity.

---

# Main Features

- Autonomous SCARA robotic arm
- Vision-based wafer detection
- Real-time defect inspection
- Vacuum pick-and-place mechanism
- Automatic Good/Reject sorting
- Precision stepper motor control
- Embedded control architecture
- Real-time wafer tracking
- Industry 4.0-inspired automation
- Expandable AI-based inspection framework

---

# System Workflow

```text
Pi Camera
        ↓
Wafer Detection
        ↓
Image Processing
        ↓
Defect Inspection
        ↓
Coordinate Generation
        ↓
SCARA Motion Planning
        ↓
Vacuum Pick & Place
        ↓
Sorting Decision
        ↓
Good / Reject Tray
```

---

# Technologies Used

### Computer Vision

- OpenCV
- Image Processing
- Object Detection
- Machine Vision

### Embedded Systems

- Raspberry Pi 5
- STM32 Microcontroller

### Robotics

- SCARA Robot Kinematics
- Motion Planning
- Stepper Motor Control
- Vacuum Pick-and-Place

### Communication

- UART Communication
- Serial Communication

### Programming

- Python
- C
- C++

### Development Tools

- VS Code
- STM32CubeIDE
- Git
- GitHub

---

# Hardware Components

## Silicon Labs Hardware (Optional)

- EFR32BG22 Wireless SoC
- EFR32MG24 Wireless SoC
- Silicon Labs Wireless Development Kit
- Bluetooth Radio Boards
- Si7021 Temperature & Humidity Sensor

---

## Main Hardware

### Processing Units

- Raspberry Pi 5
- STM32F103C8T6

### Vision System

- Raspberry Pi Camera Module 3

### Motion System

- NEMA17 Stepper Motors
- DRV8825 Stepper Drivers

### Mechanical Components

- Aluminum Profile Structure
- SCARA Arm Links
- Base Plate
- Linear Guide Rail
- Lead Screw & Nut
- 608ZZ Bearings

### End Effector

- Mini Vacuum Pump
- Vacuum Suction Cup
- Silicone Air Tube

### Sensors

- Limit Switches
- IR Sensors
- Vacuum Pressure Sensor (Optional)

### Power System

- 12V 5A SMPS
- 5V Buck Converter

---

# Applications

- Semiconductor Manufacturing
- Wafer Inspection Systems
- Electronics Manufacturing
- Industrial Automation
- Smart Factory Demonstrations
- Robotics Research
- Embedded Systems Education
- Industry 4.0 Training Platforms

---

# Future Enhancements

- AI-Based Defect Classification
- Deep Learning Inspection Models
- TinyML Integration
- Wireless Monitoring Dashboard
- Cloud Analytics Platform
- Predictive Maintenance
- Multi-Wafer Handling System
- Conveyor-Based Integration
- Digital Twin Simulation

---

# Impact

VisionPick SCARA aims to improve semiconductor manufacturing efficiency by reducing manual intervention, minimizing wafer damage, and enabling intelligent inspection and sorting.

The platform combines robotics, computer vision, embedded systems, and automation technologies to create a scalable and affordable semiconductor automation solution suitable for research, education, and industrial prototyping.

By integrating intelligent inspection with autonomous robotic handling, VisionPick SCARA demonstrates the future of smart manufacturing and Industry 4.0 automation.

---

# License

Licensed under the MIT License.
