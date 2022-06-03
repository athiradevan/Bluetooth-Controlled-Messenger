# Bluetooth Controlled Messenger 

<h3 align="left">About</h3>

This project will assist us if we want to transmit a message within a small place without making the noise. 
The project uses a Bluetooth module (HC-05) to control a 16x2 LCD panel.
We may use our smartphones to turn ON or OFF the LCD display as well as send text messages.

<h3 align="left">Components Required: </h3>

* Arduino Uno
* DMD 
* Bluetooth Module (for example: HC-05)
* Smartphone 
* Android Application 
* Breadboard
* Jumper Cables


<h3 align="left"> Software used: Arduino</h3>

* It is also important to notice that for the serial communication to work between the HC-05 and the Arduino, we need to make sure:

        HC-05 Tx pin is connected to Arduino Uno Rx pin

        HC-05 Rx pin is connected to Arduino Uno Tx pin

* When the HC-05 gadget gets a Bluetooth message, it records it to its Tx memory (transmit pin).

* We connect the HC-05 Tx pin to the Uno Rx pin because we want our Uno to receive the messages (digital 10 in our case).

