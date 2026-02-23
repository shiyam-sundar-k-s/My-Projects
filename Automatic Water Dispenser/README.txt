Auto Water Dispenser and Auto Opening Dustbin using Arduino

This project presents two simple automation systems implemented using a single Arduino microcontroller. The main objective is to improve hygiene and convenience by reducing physical contact through the use of ultrasonic sensors.

Project 1: Auto Water Dispenser

The auto water dispenser works on the principle of distance measurement using an ultrasonic sensor. When a user places their hand near the dispenser, the sensor detects the presence and sends a signal to the Arduino. The Arduino then activates a relay module, which turns ON an air pump to dispense water. After a predefined time interval, the pump is automatically turned OFF. This ensures controlled water dispensing without any manual switch operation.

Project 2: Auto Opening Dustbin

The auto opening dustbin uses an ultrasonic sensor to detect the presence of a hand near the bin. When an object is detected within a specified range, the Arduino controls a servo motor to open the dustbin lid. The lid remains open for a short duration and then closes automatically. This touchless operation helps maintain cleanliness and reduces the spread of germs.