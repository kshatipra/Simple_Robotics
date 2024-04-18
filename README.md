# Simple_Robotics
Simple ideas to learn about sensors, Arduino IDE and working of robots in various scenarios. 
---

# Simple Robots with Arduino Uno

This repository contains code for simple robots built using Arduino Uno:

1. Line Follower Robot
2. Voice Controlled Robot
3. Obstacle Avoiding Robot

## Getting Started

To get started with any of these robots, you'll need the following:

- Arduino Uno board
- Appropriate sensors and actuators depending on the robot type (e.g., IR sensors for line following, ultrasonic sensor for obstacle avoidance, microphone for voice control)
- Arduino IDE installed on your computer

## Cloning the Repository

To clone this repository, use the following command:

```
git clone https://github.com/your-username/simple-robots.git
```

## Usage

Each robot has its own directory within the repository. Navigate to the respective directory to find the Arduino sketch and any additional files necessary for that robot.

### Line Follower Robot

To use the Line Follower Robot code:

# Simple Line Follower Robot using Arduino Uno

## Components Required:

- Arduino Uno
- L293D motor driver
- IR sensor module (2 Nos)
- 7.4V or 9V battery (1 Nos)
- BO motor (2 Nos)
- Motor wheel (2 Nos)
- Castor wheel (1 Nos)
- Hobby robot chassis (1 Nos)
- Wires
- Screws

## Steps to Build:

1. **Assemble the Chassis**:
   - Place BO motors onto the chassis and secure them with screws or hot glue.
   - Attach the motor driver onto the chassis securely.

2. **Connect Motors to Motor Driver**:
   - Connect the wires from the motors to the motor driver outputs. Ensure proper polarity.

3. **Attach Wheels**:
   - Place motor wheels onto the shafts of the motors.
   - Attach the castor wheel to the chassis for stability.

4. **Mount IR Sensors**:
   - Bend the IR LED and sensor modules as shown in the instructions.
   - Place the sensors on the underside of the robot, adjusting them for the track width.

5. **Connect Sensors to Arduino**:
   - Connect the output pins of the IR sensor modules to digital pins 2 and 4 of the Arduino.

6. **Connect Motor Driver to Arduino**:
   - Connect the enable pins of the motor driver to digital pins 5 and 8 of the Arduino.
   - Connect the control pins of the motor driver to digital pins 6, 7, 9, and 10 of the Arduino.

7. **Power Up**:
   - Connect the battery to the motor driver and Arduino.
   - Ensure proper power connections and polarity.

8. **Upload Code**:
   - Use the provided Arduino code and upload it to the Arduino Uno using the Arduino IDE.

9. **Testing and Calibration**:
   - Place the robot on a black line and ensure it follows correctly.
   - Adjust IR sensor sensitivity if needed by calibrating on black and white surfaces.

10. **Finalization**:
    - Secure all connections and components.
    - Test the robot on various track configurations for optimal performance.


### Voice Controlled Robot

To use the Voice Controlled Robot code:

## Materials Required:

- Arduino Uno microcontroller
- L293D Motor driver shield
- 4pcs. DC gear motors with wheels
- HC-06 Bluetooth module
- Switch
- 7.4 Volts Lithium-Ion Battery pack

## Hardware Setup:

1. **Assemble the Robot Chassis**:
   - Mount the DC gear motors onto a rectangular plate.
   - Attach the L293D Motor driver shield securely to the chassis.

2. **Connect Motors and Power**:
   - Wire the motors to the motor driver shield.
   - Connect the HC-06 Bluetooth module and the switch.
   - Power the setup using the 7.4V Li-Ion battery pack.

3. **Software Setup**:
   - Install the Arduino IDE for programming the Arduino Uno.
   - Upload the provided Arduino code to the Arduino Uno.

4. **Android Application**:
   - Download and install the "BT Voice Control for Arduino" app from Google Play services.
   - Connect the Android device to the HC-06 Bluetooth module.

## Working Principle:

- The Android app recognizes voice commands and sends them to the Bluetooth module connected to the Arduino Uno.
- The Arduino Uno receives the commands and controls the motion of the robot based on the received commands.


### Obstacle Avoiding Robot

Sure, here's a Git README file for the Obstacle Avoiding Robot project:

---

# Obstacle Avoiding Robot (Arduino)

### Step 1: What You Need in This Project:

- Arduino UNO
- Smart robot car chassis with 2 x toy car wheels and 1 x Universal wheel (or ball casters)
- Two DC motors
- L298n motor driver
- HC-SR04 Ultrasonic Sonar sensor
- TowerPro micro servo 9g
- 7.4V 1300mah Lipo battery
- Jumper wires (male-to-male, male-to-female)
- Mini breadboard
- Ultrasonic sonar sensor mounting bracket
- Screws and nuts
- Screwdriver
- Soldering iron
- Double-sided tape (optional)
- Hot glue gun (optional)

### Step 2: Assembling the Chassis:

- Solder wires to each DC motor and fix them to the chassis.
- Attach the Universal wheel or ball caster wheel to the chassis.

### Step 3: Mounting the Components:

- Mount the Arduino UNO, L298n motor driver, and TowerPro micro servo on the chassis. Leave enough space to plug the USB cable into the Arduino for programming.

### Step 4: Preparing the Ultrasonic Sensor:

- Connect four jumper wires to the Ultrasonic sensor and mount it on the mounting bracket.
- Attach the bracket to the TowerPro micro servo already installed on the chassis.

### Step 5: Wiring Components:

- Connect the components according to the following wiring instructions provided by the project.

### Step 6: Programming Arduino UNO:

- Download and install the Arduino Desktop IDE.
- Download and install the necessary libraries for the Ultrasonic sensor function.
- Upload the provided Arduino code to the Arduino board via USB cable.

### Step 7: Power the Robot:

- Connect the Lipo battery to the L298n motor driver to power the robot.

### Step 8: Enjoy:

- Your obstacle avoiding robot is now ready to navigate and avoid obstacles in its path autonomously.

##Special Thanks to https://www.instructables.com/ & https://www.arduino.cc/ for giving out great content always and a great platform. 
## Contributing

Contributions to this repository are welcome. If you have improvements to the existing code or want to add support for additional features, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
