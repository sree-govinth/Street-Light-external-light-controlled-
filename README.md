# Street-Light-external-light-controlled-
- A very simple project using Arduino UNO, where an LED is controlled using analog inputs from a photoresistor.
- Components Used: Arduino UNO (1), LED (1), Photoresisitor (1), Resistors (100 ohms x 2), Connecting Wires, Bread Board.
- for understanding purposes, I took the max volatge required for the bulb to glow to be 75 mV.
- the whole project was implemented at Tinkercad (https://www.tinkercad.com)

Circuit Diagram:
![image](https://github.com/sree-govinth/Street-Light-external-light-controlled-/assets/155771157/21f945bf-53dd-4b07-b9bd-f70aceb77658)

Connections:
1. Connect GND and 5V of the UNO Board to "-" and "+" of breadboad respectively (check red and black wires in the diagram)
2. Connect one pin of the photoresistor to 5V; connect another pin to both GND and A1 of the UNO board (check the green wired circuit)
3. Connect "-" of the LED (short pin) to GND; Connect "+" of the LED (long pin) to Digital pin 4 of the UNO board (check the orange wired circuit).
   
Note:
- You can change the pins, but make sure to change the pin number in the code too.
- This is my way of connecting things in breadboard and UNO board. If you have other methods, go on with them!
