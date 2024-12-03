# Human Following Robot
This repository contains the Arduino sketch and instructions for building a Human Following Robot. The robot uses IR sensors, an ultrasonic sensor, and motor control to follow a human or an object while avoiding obstacles. Servo motor integration allows for directional scanning to improve accuracy.

# Features
**Human Following Mechanism:** Utilizes IR sensors to track and follow humans or objects.
**Obstacle Detection:** Uses an ultrasonic sensor to measure distance and prevent collisions.
**Motor Control:** Four DC motors controlled via the Adafruit Motor Shield for precise movement.
**Servo Motor Scanning:** Servo rotates to scan the environment for obstacles.
**Flexible Movement:**
- Moves forward when no obstacles are detected.
- Turns left or right based on sensor input.
- Stops when an obstacle is too close.
