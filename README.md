# IoT Dashboard Platform

## Description
The IoT Dashboard Platform is a web application designed for managing and monitoring Internet of Things (IoT) devices. It provides a user-friendly interface that displays real-time sensor data, allowing users to interact with and control various devices. The platform supports both manual and automatic control modes, enabling users to change device statuses and receive alerts based on sensor readings. Additionally, it features data visualization tools, such as charts and sliders, to track progress and guide users through device management.

<div style="display: flex; flex-direction: row; justify-content: center; align-items: center; gap: 10px; padding-left: 100px">
  <img src="https://github.com/anhhuy007/sig-iot/blob/master/iot1.jpg" alt="Image 1" style="width: 25%; height: 300px; object-position: cover; border-radius: 5px;" />
  <img src="https://github.com/anhhuy007/sig-iot/blob/master/iot3.jpg" alt="Image 2" style="width: 23%; height: 300px; object-position: cover; border-radius: 5px;" />
  <img src="https://github.com/anhhuy007/sig-iot/blob/master/iot4.jpg" alt="Image 3" style="width: 23%; height: 300px; object-position: cover; border-radius: 5px;" />
  <img src="https://github.com/anhhuy007/sig-iot/blob/master/iot5.jpg" alt="Image 4" style="width: 23%; height: 300px; object-position: cover; border-radius: 5px;" />
</div>


## Features
- Real-time monitoring of IoT devices
- Manual and automatic control modes
- Data visualization with charts and sliders
- Alerts and notifications for device status changes
- Keep track of IoT devices history

![SIG-IOT Web](https://github.com/anhhuy007/sig-iot/blob/master/iot2.jpg)

## Architecture
![Project architecture](https://github.com/anhhuy007/sig-iot/blob/master/app%20architecture.png)

## Installation

### Prerequisites
- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iot-dashboard.git
   cd iot-dashboard
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory and configure your environment variables as needed.

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage
- Select a sensor from the DataBox to view its details and control its status.
- Use the sliders to adjust settings and monitor progress.
- Receive alerts for any critical changes in sensor data.

## Technology Stack
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,tailwind,ts,postgres,arduino" />
  </a>
</p>
