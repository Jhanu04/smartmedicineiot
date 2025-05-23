The Smart Medicine Box is an IoT-based solution designed to help users take their medications on time. 
It uses the ESP8266 NodeMCU to connect to the Blynk cloud platform, where users can set schedules and receive real-time alerts.
At the scheduled time, the system activates a buzzer as a reminder. If hand motion is detected using the ultrasonic sensor, the servo motor automatically opens the box lid, making access easy for the user.

The system keeps track of medicine intake and updates the internal pill count. When the count falls below a set threshold, a refill alert is triggered. 
The entire setup is managed through the Blynk app, which uses virtual pins to control timing, notifications, and stock status. 
The Arduino IDE is used for programming, along with necessary libraries like NewPing, Servo, and Blynk.

Testing confirmed accurate alert timings, reliable motion detection within 30 cm, and smooth motor operations. 
The Smart Medicine Box not only improves medication adherence but also simplifies stock management.

