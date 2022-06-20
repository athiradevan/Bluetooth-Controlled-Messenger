# Bluetooth Controlled Messenger 

<h3 align="left">About</h3>

This project will assist us if we want to transmit a message within a small place without making the noise. 
The project uses a Bluetooth module (HC-05) to control a 16x2 LCD panel.
We may use our smartphones to turn ON or OFF the LCD display as well as send text messages.


<h3 align="left"> Software used: Arduino</h3>

<h3 align="left">Components Required: </h3>

* Arduino 
* DMD 
* Bluetooth Module (for example: HC-05)
* Smartphone 
* Android Application 
* Breadboard
* Jumper Cables



* It is also important to notice that for the serial communication to work between the HC-05 and the Arduino, we need to make sure:

        HC-05 Tx pin is connected to Arduino Uno Rx pin

        HC-05 Rx pin is connected to Arduino Uno Tx pin

* When the HC-05 gadget gets a Bluetooth message, it records it to its Tx memory (transmit pin).

* We connect the HC-05 Tx pin to the Uno Rx pin because we want our Uno to receive the messages (digital 10 in our case).
* Connect your Arduino to Power supply
* Turn on the Bluetooth in your device, Search for new device, Click on Hc05 once it appear.
* Download 'Arduino Bluetooth Control' app and connect to HC-05.
* Send "1" to turn on the LCD display.

  Send any message to display on LCD.

  Send "2" to turn off the LCD display.


