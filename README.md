# mars-club-task-1 EC25B1127 M SATYA PRAPUL SIDDHARDH
Automatic Night Lamp using photo resistor
-- Objective--
The aim of this project is to make a light that turns ON automatically in dark and turns OFF in light.
--- Components Used--
Arduino Uno
photo resistor
10kΩ Resistor
LED
220Ω Resistor
Breadboard
Connecting wires
-- Working--
In this project, an photo resistor is used to detect light. When there is more light, the resistance of photo resistor decreases, and when it is dark, the resistance increases.
The Arduino reads this value and based on it, controls the LED. When it is dark, the LED turns ON, and when there is light, the LED turns OFF.
-- Code Logic--
First, the Arduino reads the value from photo resistor using analog pin. Then it checks whether the value is above or below a certain limit. If it is dark, the LED is switched ON. Otherwise, it remains OFF.
--Challenges Faced--
I faced some difficulty in connecting the circuit properly.
--Conclusion--
This project helped me understand how sensors work with Arduino. It is useful in real life for automatic street lights and saving electricity.
