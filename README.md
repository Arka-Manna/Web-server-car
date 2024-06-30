
# ESP8266/ESP32 RC Car with Web-Based Control

This project demonstrates how to control an RC car using an ESP8266 or ESP32 microcontroller through a web-based interface. The web interface allows users to remotely control the car's movements, lights, and horn by connecting to a local WiFi network.

## Key Features

### Remote Car Control
- Control the car's movements: forward, backward, left, and right.
- Stop the car with a single button press.

### Light and Horn Control
- Turn the car's lights on and off.
- Activate and deactivate the car's horn.

### Web-Based Interface
- The web interface is accessible on any device with a web browser (desktop, tablet, smartphone).
- Simple and user-friendly design with buttons for each control action.

### Real-Time Feedback
- Immediate response to control commands sent from the web interface.
- Visual and auditory feedback from the car (lights and horn).

## Technical Details

### Components
- **Microcontroller**: ESP8266 or ESP32, which offers low cost and built-in WiFi capabilities.
- **Motor Control**: Four GPIO pins control two motors for movement.
- **Light and Horn Control**: Two GPIO pins control the light and horn.

### Web Server
- The microcontroller runs a web server on port 80 to serve the control interface.
- The web interface uses HTML, CSS, and JavaScript for structure, styling, and interactivity.

### Circuit Connections
- **Motors**: Connected to GPIO pins D1, D2, D3, and D4.
- **Light**: Connected to GPIO pin D6.
- **Horn**: Connected to GPIO pin D7.


### Author: ARKA MANNAA

