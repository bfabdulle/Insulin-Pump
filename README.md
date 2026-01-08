# Insulin Pump Simulation (Qt / C++)

## Overview

This project is a desktop-based simulation of the **t:slim X2 insulin pump**, designed to model real-world insulin pump behavior in a safe, controlled software environment. The application demonstrates how a safety-critical medical device can manage insulin delivery, system state, and user interaction while maintaining reliability and traceability.

The simulator focuses on realistic **basal and bolus insulin delivery**, dynamic system control, and a responsive graphical user interface, making it well suited as a demonstration of object-oriented design, algorithmic decision-making, and GUI development in C++.

## GUI Demo
https://github.com/user-attachments/assets/dc36f22a-7bdf-4e0b-a8f9-a4805c76e90c


## Key Features

- Basal insulin delivery algorithm inspired by Control-IQ behavior  
- Bolus insulin calculation with user-defined inputs  
- Start, stop, and resume insulin delivery controls  
- Battery and insulin cartridge simulation  
- Error handling and safety checks  
- Event history and error logging for traceability  
- Insulin delivery graphing for real-time visualization  
- Qt-based GUI focused on clarity and usability  

## Technologies Used

- C++  
- Qt Framework (Qt Creator, Qt Widgets)  
- Object-Oriented Design  
- Unit Testing  
- UML & System Modeling  

## Architecture & Design

The system is structured using modular, object-oriented components that separate insulin logic, system state management, and user interface concerns. Core insulin behavior is encapsulated in dedicated classes, while the GUI layer communicates with the underlying logic through well-defined interfaces.

Design decisions prioritize maintainability, extensibility, safe handling of state changes, and transparent system feedback through logs and graphs.

## Running the Application

1. Clone the repository:
   ```bash
   git clone <repository-url>

2. Open the project in Qt Creator

3. Build the project using the build (hammer) icon

4. Run the application using the run button


## Project Structure

* insulinpump.h / insulinpump.cpp — Core insulin pump logic

* mainwindow.* — GUI logic and interaction

* tests.cpp — Unit tests for system components

* mainwindow.ui — Qt UI layout

## Demonstration


## Why This Project Matters

* This project demonstrates experience with:

* Developing safety-critical system simulations

* Implementing state-driven logic and control algorithms

* Building interactive desktop applications in C++

* Designing software with real-world constraints in mind
