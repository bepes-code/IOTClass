# Project Overview
This project, developed during HackUpc2024 over 36 hours of intense collaboration, showcases the innovative efforts of a dedicated team comprising four individuals. The primary objective was to address the challenge of energy consumption monitoring and optimization within classroom environments.

# Key Features
- **Light Control**: The system offers dual control mechanisms for regulating room lighting: through a web interface and traditional switch operation. Leveraging PIR (Passive Infrared) sensors, the system intelligently turns off lights in unoccupied rooms, while light intensity adjusts dynamically based on ambient light levels for optimal energy efficiency.

- **Temperature Control**: Utilizing temperature sensors, the system continuously monitors room temperature. When temperatures exceed predefined thresholds, the air conditioner activates to cool the room, and conversely, the heater activates to warm the room when temperatures drop below specified limits.

- **Access Control**: Access to the classroom is managed through RFID card authentication. Each RFID card is registered in the system's database, granting access only to authorized individuals. Additionally, entry times of teachers are logged for generating comprehensive attendance reports.

- **Voice Level Monitoring**: The system incorporates microphone-based voice level monitoring. When voice levels surpass predefined thresholds, lights automatically illuminate, creating a conducive environment for interaction. Conversely, lights dim when voice levels recede, optimizing energy usage.

- **Party Mode**: An engaging feature, Party Mode, transforms the ambiance by turning off lights and initiating music playback via connected speakers. Teachers can conveniently select music choices through the web interface, enhancing classroom dynamics.

# Hardware Components
- x2 ESP32
- x1 PIR Sensor
- x4 Relays (Door access, electrovalve, lighting, fans)
- RFID Detector
- x1 Temperature Sensor
- x1 Light Sensor
- x1 Microphone
- x1 Speaker
- x1 RGB LED
- x8 LEDs

# Platform and Technologies
The project utilizes a sophisticated platform and a blend of cutting-edge technologies:
- **Application**: An intuitive application offers sensor data visualization and control features for lighting and music. Grafana serves as the primary tool for sensor data visualization, complemented by custom APIs for actuator control.
- **Architecture**: The project architecture is powered by:
  - MQTT for communication
  - PostgreSQL database for data storage
  - Grafana for data visualization
  - Angular for the frontend
  - FastAPI for backend services
  - Docker for containerization
  - Arduino for hardware interfacing

# Credits
- **Aleix(bepes-code)**: Hardware development and communications
- **Jonas**: Backend development
- **Laura**: Frontend development
- **Chave**: Contributed to hardware development and prototype construction

# Extras
 - Devpost: 
 - **This projects get the 3r position in the HackUPC 2024**
