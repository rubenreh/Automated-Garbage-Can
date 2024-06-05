One of the projects I’m particularly proud of is an older creation: an automated garbage can designed to assist people with disabilities. This project reflects my passion for using technology to solve real-world problems and enhance everyday life.

How It Works
The automated garbage can operates by detecting when trash approaches it. When an object, such as a piece of trash, comes near the sensor, the lid opens automatically, providing a hands-free experience. This feature is especially beneficial for individuals with physical limitations, making the simple task of disposing of waste much easier.

Components Used
The key components that make this project work are:

Arduino Uno R3: The microcontroller that serves as the brain of the system.
Ultrasonic Sensor: This sensor detects the proximity of an object, in this case, the trash, by emitting sound waves and measuring the time it takes for the waves to bounce back.
Servo Motor: The servo motor is responsible for opening and closing the garbage can lid. When the ultrasonic sensor detects an object within a certain range, it sends a signal to the servo motor to move, lifting the lid.
The Process
Detection: The ultrasonic sensor continuously sends out sound waves. When it detects an object within a predefined distance, it triggers the next step.
Signal Processing: The sensor sends a signal to the Arduino, which processes the information and determines that an object (trash) is approaching.
Lid Operation: The Arduino then sends a command to the servo motor, causing it to rotate and open the lid of the garbage can. Once the trash is disposed of and no further motion is detected, the servo motor closes the lid.
This project was an exciting and educational experience, reinforcing my belief in the power of technology to improve daily life. It also showcased the versatility of Arduino and how even simple components can come together to create something genuinely impactful.
