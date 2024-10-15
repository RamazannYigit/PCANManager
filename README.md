# PCANDbc
**PCANDbc: DBC File Upload and CAN Message Analysis Application**

This project implements a PCAN integrated application that loads and analyzes a DBC (Database CAN) file using the Qt framework. The application utilizes CAN bus communication for real-time data exchange with the vehicle's systems.

<div style="display: flex; justify-contect: space-between;">
   <img src="Photo's/1.png" alt="1.png" width="500" />
</div>

## Project Overview
The PCANDbc application provides a sophisticated interface for monitoring and controlling vehicle systems. It employs PCAN (Peak CAN) hardware for bidirectional communication with the car's CAN bus, enabling the real-time acquisition and control of various parameters.

<div style="display: flex; justify-content: space-between;">
   <img src="Photo's/3.png" alt="3.png" width="500" />
   <img src="Photo's/4.png" alt="4.png" width="500" />
</div>

## Features
- Real-time CAN message analysis  
- DBC file loading and interpretation  
- Signal filtering and management  
- Graphical data visualization  
- User-friendly interface design  
- Seamless integration with PCAN hardware

<div style="display: flex; justify-content: space-between;">
   <img src="Photo's/7.png" alt="7.png" width="350" />
   <img src="Photo's/9.png" alt="9.png" width="350" />
   <img src="Photo's/10.png" alt="10.png" width="350" />

## Technical Details

### PCAN Communication
- Receives real-time data from vehicle sensors (temperature, humidity, etc.)
- Sends control commands to adjust settings
- Implements error handling and data validation for robust operation

### QT Framework
- Utilizes QT for creating a responsive and intuitive user interface
- Implements multi-threading for smooth UI performance during data processing

### Data Processing
- Real-time parsing and interpretation of CAN messages
- Algorithmic control to maintain desired conditions

## Technologies and Tools
- QT Framework
- C++
- PCAN-Basic API
- CAN bus protocol
- Git for version control

## Setup and Installation
Follow these steps to set up and run the project:

1. **Required Software:**
   - QT
   - Git
   - PCAN-Basic API
2. Install these software on your computer.
3. Clone the project:
   ```bash
   git clone https://github.com/yourusername/PCANDbc.git
   cd PCANDbc
4. Open QT Creator.
5. Click on "Open Project" within QT Creator.
6. Select and open the CMakeLists.txt file in the downloaded project folder.
7. QT Creator will validate and load all project files to your screen.
8. You can now compile and run the project.

## Usage
1. **Connect the PCAN device to the vehicle.**
2. **Launch the application.**
3. **In the application interface, click on the button or option corresponding to the action you want to perform.**
4. **The selected action will be sent as data to the vehicle through the PCAN device.**

**Note:** The bytes and IDs of incoming or outgoing data from the PCAN device may vary depending on your vehicle or system. Therefore, you may need to examine the code content and make necessary adjustments to adapt the application to your system.
