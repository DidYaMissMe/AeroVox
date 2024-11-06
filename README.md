# AeroVox

## Overview
AeroVox is a web-based application developed using Vue.js that enables users to control drones through voice commands and implement 3D spatial constraints to ensure safe and efficient operations. Building upon the Drone Engineering Ecosystem (DEE), AeroVox enhances drone accessibility and safety by offering intuitive voice control and robust spatial enforcement mechanisms.

## Key Features
- **Voice Commands**
  - **Arming the Drone**: Initiate drone systems with voice instructions.
  - **Takeoff**: Command the drone to take flight.
  - **Navigation**: Direct the drone to specific directions (e.g., heading north).
  - **Altitude Adjustment**: Modify the drone's altitude using voice commands.
  - **Return-to-Home**: Safely land the drone by issuing return commands.
  - **Additional Flight Controls**: Manage various flight parameters effectively.

- **3D Spatial Constraints**
  - **Geofencing**: Define three-dimensional boundaries to restrict drone movement within designated airspace.
  - **Altitude Restrictions**: Set maximum and minimum altitude limits to prevent unauthorized flight levels.

- **Real-Time Interaction**
  - **Telemetry Monitoring**: View live data on drone status, including location, speed, and altitude.
  - **Data Visualization**: Access real-time visual feedback through an interactive dashboard.

- **Secure Communication**
  - **MQTT Protocol**: Efficient, real-time messaging between the drone and control interface.
  - **User Authentication**: Secure access through robust authentication mechanisms.
  - **Data Encryption**: Protect data transmission against unauthorized access.

## Installation and Setup
To set up and run AeroVox on your local machine, follow these steps:

### Prerequisites
- **Node.js** (Version 16.14.2 or higher)
- **Vue CLI** (Version 4.5.15 or higher)
- **MQTT Broker** (e.g., Mosquitto)

### Installation Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/DidYaMissMe/AeroVox.git
   cd AeroVox
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure MQTT Broker**
   - Ensure you have access to an MQTT broker.
   - Update the MQTT broker details in the configuration file (`config.js` or equivalent) as needed.

4. **Run the Development Server**
   ```bash
   npm run serve
   ```
   The app will be accessible at `http://localhost:8080` in your browser.

## Usage
### How to Use AeroVox
1. **Connect to MQTT Broker**
   - Ensure the drone is connected to an MQTT broker for real-time communication.

2. **Issue Voice Commands**
   - Use your microphone to issue commands such as:
     - "Arm"
     - "Take off"
     - "Go north"
     - "Go [altitude in meters]"
     - "Return"

3. **Monitor Telemetry**
   - View live telemetry data including drone location, altitude, and status within the web interface.

4. **Enforce Spatial Constraints**
   - Set up 3D geofences to define the drone’s operational area, ensuring it stays within designated boundaries.

## Demo
Experience a demonstration of AeroVox by watching the following video:
- **[AeroVox Demo Video](https://www.youtube.com/)**: This video showcases the primary functionalities of AeroVox, including voice commands, 3D spatial constraints, and real-time telemetry monitoring.

## Code Walkthrough
Gain insights into the application's codebase with our detailed walkthrough video:
- **[AeroVox Code Walkthrough](https://www.youtube.com/)**: This video provides a comprehensive tour of the code structure, explaining key components developed with Vue.js, integration of MQTT for real-time communication, and implementation of voice control functionalities.

## Contribution Guidelines
We welcome contributions to enhance the functionality and performance of AeroVox. To contribute:

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/YourFeature
   ```

3. **Commit Your Changes**
   ```bash
   git commit -m "Add your feature"
   ```

4. **Push to the Branch**
   ```bash
   git push origin feature/YourFeature
   ```

5. **Open a Pull Request**
   - Provide a clear description of your changes and the problem they solve.

## Contact
For any inquiries or feedback, please contact the author of this repo.
