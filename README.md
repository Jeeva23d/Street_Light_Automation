
# Street_Light_Automation

Overview
This project implements Street Light Automation using IoT and smart sensors to optimize energy consumption, monitor faults, and enable remote control of street lights. It uses real-time sensor data to adjust lighting intensity based on environmental conditions and traffic, ensuring sustainable and efficient urban infrastructure.

**Features:**

Automated Day/Night Detection: Automatically switches street lights on/off based on light levels.
Fault Detection: Identifies faulty light posts and logs the status.
Traffic-Based Brightness Adjustment: Detects motion and dynamically adjusts light intensity.
Energy Optimization: Reduces energy usage by dimming lights when traffic is low.
Solar Integration: Charges the system during the day and operates at night.

**Code Overview:**

The project uses an Arduino-based implementation with the following features:

Microcontroller: Configured to read from sensors and control LEDs.

Input Sensors:
Light-Dependent Resistors (LDR): Measure ambient light levels.
Infrared (IR) Sensors: Detect motion for traffic-based lighting.
Solar Sensors: Monitor solar panel activity.

**Outputs:**

LEDs simulate street lights.
Serial monitoring for debugging and fault reporting.

**Project Structure**

**Sensors and Inputs:**

LDR for light level detection.
IR sensors for motion detection.
Solar sensors for monitoring power.

**Control Logic:**

Autonomous switching of lights.
Fault detection for each post.
Dynamic brightness adjustment.

**Outputs:**

Serial monitoring for real-time status updates.
LED brightness controlled based on sensor inputs.

**Hardware Requirements:**

Microcontroller (e.g., ESP32 or Arduino)
LDR Sensors
IR Motion Sensors
LEDs (or equivalent lighting systems)
Solar Panels (optional for solar integration)
Resistors and Breadboard for prototyping

**Setup Instructions**


**Clone the Repository:**

git clone https://github.com/yourusername/street-light-automation.git
cd street-light-automation

Upload Code:

Open the provided code in the Arduino IDE.
Select the appropriate board and port from the Tools menu.
Upload the code to the microcontroller.

**Connect Hardware:**

Follow the pin configuration in the code to connect the sensors and LEDs to the microcontroller.
Flowchart

**The project workflow**:

Detect day or night using the LDR sensor.
Adjust light brightness based on traffic using IR sensors.
Log faulty lights for maintenance.
Manage solar charging during the day.


**Future Enhancements**




https://github.com/user-attachments/assets/e80d618a-0ed4-44e3-a1ed-7790420ece8e



https://github.com/user-attachments/assets/1bb43a71-bed5-4fbc-a950-f27d97e8ddd3





![WhatsApp Image 2024-12-18 at 21 10 20](https://github.com/user-attachments/assets/53a7d578-59ae-4583-a4fd-fbeed66e320e)
![WhatsApp Image 2024-12-18 at 21 10 20 (1)](https://github.com/user-attachments/assets/1c5a54f1-1f30-44fb-b036-52678c6f63d6)





Predictive Maintenance: Use analytics for proactive fault management.
Smart City Integration: Connect to centralized smart city dashboards.
Renewable Energy: Expand solar integration for energy sustainability.

