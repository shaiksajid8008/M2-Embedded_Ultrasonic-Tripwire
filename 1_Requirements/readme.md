# Requirements:
## ULTRASONIC TRIPWIRE
# Introduction
* the main is to  Create a burglar-tripwire with the ultrasonic sensor. And These active detectors transmit ultrasonic sound waves that are inaudible to humans using frequencies between 15 kHz and 75 kHz. The Doppler shift principle is the underlying method of operation which detects a change in frequency due to object motion. This detection occurs when the object must cause a change in the ultrasonic frequency to the receiver relative to the transmitting frequency.
# Research
* Ultrasonic sensors work by emitting sound waves at a frequency too high for humans to hear. They then wait for the sound to be reflected back, calculating distance based on the time required. This is similar to how radar measures the time it takes a radio wave to return after hitting an object.
* While some sensors use a separate sound emitter and receiver, it’s also possible to combine these into one package device, having an ultrasonic element alternate between emitting and receiving signals. This type of sensor can be manufactured in a smaller package than with separate elements, which is convenient for applications where size is at a premium.
# Cost And Features
## costs:
The Cost for the Ultrasonic Tripwire The running cost needs an working system with an the battery backsups.and we well use in this project is buzzer,ultrasonic sensor,Arduino nano R3 And it well cost more
## Features:
f this all sounds interesting, you can try it out yourself very easily using an Arduino and an HC-SR04 sensor. Shown above is the compact and inexpensive Arduino Nano, but any other development board should also work. Gather the components (Arduino, HC-SR04, wires, and breadboard) and go into the Arduino IDE and install the “NewPing” sensor library.
## Hardware Requirements:
- Ultrasonic sensor
- buzzer
- Arduino nano R3
- Jumper Wires
- Bread Board
# software requirements:
- c
- Arduino IDE

## Defining our System
* While radar and ultrasonic sensors can be used for some of the same purposes, sound-based sensors are readily available—they can be had for just a couple dollars in some cases—and in certain situations, they may detect objects more effectively than radar.For instance, while radar, or even light-based sensors, have a difficult time correctly processing clear plastic, ultrasonic sensors have no problem with this. In fact, they’re unaffected by the color of the material they are sensing.On the other hand, if an object is made out of a material that absorbs sound or is shaped in such a way that it reflects the sound waves away from the receiver, readings will be unreliable.
- To use the IFTTT, sign in to your IFTTT account if you already have one or
create an account.
- Now, click on the documentation to get the key which will be used in our
programming part
- After that click on create
- Next, search for webhooks and select it
- After clicking the webhooks, now you want to select “Receive a web
request” and give an event name as per your wish. In my case, I have given
buzzer
