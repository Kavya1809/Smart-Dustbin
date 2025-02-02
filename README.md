
**Ultrasonic Distance Measurement with Servo Control**
This project demonstrates the use of an ultrasonic sensor (HC-SR04) to measure the distance of an object and control a servo motor based on the measured distance. When the measured distance falls below a set threshold (30 cm), the servo motor is triggered to move, simulating an action (e.g., opening or closing a mechanism like a lid or cap).

**The key components used in this project are:**

Ultrasonic sensor (HC-SR04): To measure the distance between the sensor and an object.
Servo motor: To perform a physical action (e.g., opening/closing a cap) when the object comes within a certain range.
Arduino Uno (or any compatible board): The central microcontroller that reads the distance and controls the servo based on that measurement.
Features
Uses ultrasonic waves to measure the distance to an object.
Average of 3 distance measurements is calculated for greater accuracy.
Servo motor is triggered to perform an action when the object is within a specified distance.
The servo motor is initially set to a closed position (e.g., lid closed) when powered on.


**Components Required**
Arduino Board (e.g., Arduino Uno)
HC-SR04 Ultrasonic Sensor
Servo Motor
LED (optional for indication)
Jumper wires


**Pin Configuration**
Trig Pin: Connected to Pin 5 on Arduino
Echo Pin: Connected to Pin 6 on Arduino
Servo Pin: Connected to Pin 7 on Arduino
LED (optional): Connected to Pin 10 on Arduino


**How It Works**
The Arduino reads the distance using the ultrasonic sensor.
If the measured distance is less than 30 cm, the servo motor is triggered to perform an action (e.g., open a cap).
The servo motor stays in the triggered position for a set time before returning to its default position.
The distance is continuously displayed in the serial monitor.


**Installation Instructions**
Download or clone this repository.
Open the Ultrasonic_Servo_Control.ino file in the Arduino IDE.
Connect the components to your Arduino board as per the pin configuration mentioned above.
Upload the code to your Arduino board.
Open the serial monitor to view the distance measurements.
**Future Enhancements**
Integrate more sensors for greater accuracy.
Add a user interface to adjust the threshold distance.
Integrate with IoT systems to remotely monitor the distance and control the servo.
