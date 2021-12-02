# Requirements:
## ULTRASONIC TRIPWIRE
# Introduction
* the main is to  Create a burglar-tripwire with the ultrasonic sensor. And These active detectors transmit ultrasonic sound waves that are inaudible to humans using frequencies between 15 kHz and 75 kHz. The Doppler shift principle is the underlying method of operation which detects a change in frequency due to object motion. This detection occurs when the object must cause a change in the ultrasonic frequency to the receiver relative to the transmitting frequency.
# Research
* Ultrasonic sensors work by emitting sound waves at a frequency too high for humans to hear. They then wait for the sound to be reflected back, calculating distance based on the time required.This is similar to how radar measures the time it takes a radio wave to return after hitting an object.
* While some sensors use a separate sound emitter and receiver,it’s also possible to combine these into one package device,having an ultrasonic element alternate between emitting and receiving signals.This type of sensor can be manufactured in a smaller package than with separate elements,which is convenient for applications where size is at a premium.
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
- ATmega16 microcontroller needs to transmit at least 10 us trigger pulse to the HC-SR04 Trig Pin.
- After getting a trigger pulse, HC-SR04 automatically sends eight 40 kHz sound waves and the microcontroller waits for rising edge output at the Echo pin.
- When the rising edge capture occurs at the Echo pin which is connected to an input of ATmega16, start Timer of ATmega16 and again wait for a falling edge on the Echo pin.
- As soon as the falling edge is captured at the Echo pin, the microcontroller reads the count of the Timer. This time count is used to calculate the distance to an object.
## SWOT Analysis
- this project is use full for house activity sensor in emergency alert.
- The system detects the abnormal activity and sends immediately an emergency alert
- The main aim to recognize the any abnormal activity and their movements
## 4W's and 1'H
* What: This project is very use full for human fall activity using ultrasonic sensor
* Where:To overall maintaince becomes a easily
* When:The system detects the abnormal activity and sends immediately an emergency alert
* Why: The tools organise this information in a way that makes it easy for you to find the entires again the data may also be searchable.
* How: it works simple and easily using ultrasonic Sensor
## Detail Requirements
_HIGH LEVEL REQUIREMENTS_
|   ID  |    Descripition   |        Status      |
| ----  |  ---------------- | ------------------ |
| HLR1  | Login and sign up | user need to access |
| HLR2  | search filter     | filter by princes abd product |
## final report
* In this paper, we monitor Patient through a sensor. Human activity recognition using ultrasonic sensor provides fast and accurate decision making in health care application.
* The system detects the abnormal activity and sends immediately an emergency alert.
* The main aim of the system is to predict the activity before the event occurs.
### Design
## High level design
![image](https://www.researchgate.net/profile/Prerna-Sharma-8/publication/336552267/figure/fig4/AS:814153979666432@1571120843237/Flowchart-of-intelligent-object-detection-and-avoidance-system-V-CONCLUSIONS-The-goal-of.ppm)
## Block diagram
![image](https://www.researchgate.net/profile/Rashidah-Olanrewaju/publication/323714986/figure/fig1/AS:657387664969732@1533744841839/System-operation-flowchart.png)

## Behavioural Diagrams
![image](https://user-images.githubusercontent.com/91029826/144367461-52d7c8b8-a474-4ce7-84e4-5db6326b2d5f.png)
# Test Plan
## High Level Test Plan
| ID | Description | Ex I/P | Ex O/P | Actual Output |
| -- | ----------- | ------ | ------ | ------------- |
| HLT1 | Power On | Power supply | LCD ON | PASS |
| HL2 | Sensor  | Objects In the range  | Objects detected | PASS |
| HLR3 | Output | Output of the Sensor | Distance of objects | PASS |

## Low Level Test Plan 
| ID | Description | Ex I/P | Ex O/P | Actual Output |
| -- | ----------- | ------ | ------ | ------------- |
| LLT1 | Objects Range  | 20cm   | Ojects in range | PASS |
| LLT2 | Objects Range  | 100cm  | Objects Not in range | PASS |
### Expected output
  __OFF__

![image](https://user-images.githubusercontent.com/91029826/144368442-4565e888-4cf0-4dd4-8e62-5d31654e1dd5.png)

  __ON__
  
  ![image](https://user-images.githubusercontent.com/91029826/144378249-08c3fd8f-ac64-4d57-bf84-5a199f439f51.png)
