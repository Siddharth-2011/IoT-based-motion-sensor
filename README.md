# IoT-based-motion-sensor
**IoT-Based Motion Sensor Project**
The IoT-Based Motion Sensor project is designed to detect motion using a Passive Infrared (PIR) sensor and provide real-time alerts to the user in case of any intruder presence. The project utilizes a NodeMCU microcontroller for Internet connectivity, enabling remote notifications via the Telegram mobile application. Additionally, a buzzer is employed to sound an audible alarm when motion is detected, providing an immediate alert to the user within the proximity of the sensor.
**Functionality**
The IoT-Based Motion Sensor project operates as follows:

1. The PIR sensor continuously monitors the surroundings for any detected motion.
2. Upon detecting motion, the NodeMCU microcontroller receives a signal from the PIR sensor.
3. The microcontroller activates the buzzer, emitting an audible alert to indicate the presence of an intruder.
4. Simultaneously, the microcontroller establishes an Internet connection using the NodeMCU's built-in Wi-Fi capabilities.
5. If the user is not within the vicinity of the buzzer, the microcontroller sends a notification to the user's mobile phone via the Telegram mobile application.
6. The user receives the notification on their mobile phone, providing them with an alert about the detected motion in their house.
7. The user can then take appropriate action based on the received notification.

**Repository Structure**
The repository is structured as follows:

/IDE code: This directory contains the source code for the IoT-Based Motion Sensor project.
/report: This directory includes the circuit diagrams, schematics necessary to assemble the hardware setup and the other details of teh project.
/ppt: This directory provides additional documentation, such as a powerpoint presentation to get more information about the project.
/image: This directory is the final image of our project.
/Telegram notification: This directory is the screenshot the telegram notification which the user receiver on his/her mobile phone.

**Getting Started**
1. To get started with the IoT-Based Motion Sensor project, follow these steps:
2. Set up the hardware components according to the circuit diagrams provided in the /report directory.
3. Install the required libraries or dependencies mentioned in the project's source code.
4. Configure the NodeMCU microcontroller with your Wi-Fi credentials to establish an Internet connection.
5. Update the necessary variables or configuration settings in the source code to match your requirements (e.g., Telegram API credentials).
6. Upload the code to the NodeMCU microcontroller using an appropriate programming tool or the Arduino IDE.
7. Ensure that the PIR sensor is properly positioned and connected to the microcontroller.
8. Power on the setup and test the motion detection functionality.
9. Verify that the buzzer sounds when motion is detected.
10. If you are not within the proximity of the buzzer, check your mobile phone for the received notification via the Telegram mobile application.
11. Customize or modify the project as desired, exploring additional features or integrations.

Enjoy building your IoT-Based Motion Sensor project and enhancing your home security!
