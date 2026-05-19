Project Overview:
This project presents an end-to-end Internet of Things (IoT) solution engineered to mitigate industrial and domestic electrical hazards, such as power surges, overheating, gas leaks, and electrical fires. By combining continuous multi-sensor tracking with an automated trip mechanism, the system shifts safety infrastructure from a traditional reactive fuse model to a proactive, intelligent ecosystem.

Key Features & Functionalities:

Multi-Sensor Data Fusion: The system continuously tracks environmental and electrical parameters simultaneously using an array of six specialized sensors: MQ4 (gas leaks), LM35 (overheating), ACS712 (current spikes), a Voltage Sensor (over-voltage), a Vibration Sensor (structural/mechanical faults), and a PIR sensor (unauthorized physical access near high-voltage zones).

Automated Hazard Mitigation: Programmed with real-time microcontroller logic to act as an automated fail-safe. If any sensor threshold is crossed, the system immediately triggers relay modules to isolate the electrical loads and cut power before damage occurs.

Dual-Channel Alert System: Leverages an ESP8266 Wi-Fi module to concurrently host a responsive, local HTML web dashboard for nearby monitoring, while utilizing the Blynk IoT API to log emergency events (like power cuts) and push instant alert notifications to a user’s mobile device.

Technical Stack:

Hardware: Arduino UNO, ESP8266 Wi-Fi Module, Relays, Buzzer, and Sensor Array (MQ4, LM35, ACS712, Voltage, Vibration, PIR).

Software & Protocols: C++ (Arduino IDE), Blynk IoT Platform, HTML/CSS, Web Servers, and Cloud APIs.

Impact:
The project delivers a scalable, cost-effective framework for real-time risk assessment, significantly reducing response times during critical electrical faults and improving overall operational safety.
