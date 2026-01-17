# FINAL-PROJECT-Student-Portfolio-for-COSC-111

Lab act#1
This program from our activity controls 5 LEDs using an array to store their pin numbers, it basically turns the lights on one by one with a 1-second delay, and once they are all lit, it turns them off one by one in the exact same order

Lab act#2
This code from our activity uses analogWrite to create a smooth fading effect instead of just turning the lights on and off instantly. It loops through the LEDs to fade them in one by one, keeping each one turn on for a second, and then runs a second loop to fade them all out in sequence before restarting.

Lab act#3
This code from our activity creates a fire detection system that monitors both temperature and light levels using a thermistor and a photoresistor so basically if the temperature goes above 50 degrees and the light level is brighter than 220 at the same time, it triggers the LED and buzzer to blink rapidly to warn you about a potential fire.

Lab act#4
This code from our activity monitors the temperature, and if it gets hotter than 50°C, it triggers an alarm where the LED blinks continuously; the alarm stays on until you manually type "stop" in the Serial Monitor to turn it off.

Lab act#5
This is the first activity we use python and arduino, this activity's code establishes a connection between a computer and an Arduino using Python to control LEDs remotely. Basically, the Python script runs a menu on the PC where you can select commands like toggling specific colors Red, Green, Blue or turning them all on and off then sends those characters over the serial port to the Arduino, which then receives the signal and lights up the corresponding LEDs.

Lab act#6
This code from our activity sets up a two way communication system where pressing a physical button on the Arduino sends a signal to the Python script on the computer; the Python script then recognizes the button press and sends a command back to the Arduino to toggle the correct Red, Green, or Blue LED.

Lab act#7
This is the Final Activity for our IoT subject, and honestly, it was the most difficult one because we almost didn't manage to make it work. The project uses FastAPI to create a web server that communicates with the Arduino, allowing us to control the Red, Green, and Blue LEDs from a browser while the Arduino simultaneously reports back to the server whenever we press the physical buttons.
