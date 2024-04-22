# Street-Light-external-light-controlled-
- A very simple project using Arduino UNO, where an LED is controlled using analog inputs from a photoresistor.
- Components Used: Arduino UNO (1), LED (1), Photoresisitor (1), Resistors (100 ohms x 2), Connecting Wires, Bread Board.
- for understanding purposes, I took the max volatge required for bulb to glow as 75 mV.
- the whole project was implemented at Tinkercad (https://www.tinkercad.com)

Circuit Diagram:
![image](https://github.com/sree-govinth/Street-Light-external-light-controlled-/assets/155771157/21f945bf-53dd-4b07-b9bd-f70aceb77658)

Connections:
1. GND and 5V are connected to "-" and "+" of breadboad (check red and black wires in the diagram)
2. One pin of photoresistor is connected to 5V; Another pin is connected with both GND and A1 (check the green wired circuit)
3. Connect "-" of the LED (short pin) to GND; Connect "+" of the LED (long pin) to Digital pin 4 of the UNO board (check the orange wired circuit).
 
