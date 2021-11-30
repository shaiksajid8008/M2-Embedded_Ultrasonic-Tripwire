### Table no: High level test plan
|  ID  |   Test scenario  |   Test Data     |
|----- | -----------------|-----------------                                        |
| 1 |   Main men         | ATmega328 microcontroller needs to transmit at least 10 us trigger pulse to the HC-SR04 Trig Pin. |
| 2 | STEPS TO ECHO pin    | After getting a trigger pulse, HC-SR04 automatically sends eight 40 kHz sound waves and the microcontroller waits for rising edge output at the Echo pin. |
| 3 | Documentation Program | When the rising edge capture occurs at the Echo pin which is connected to an input of ATmega328, start Timer of ATmega16 and again wait for a falling edge on the Echo pin. |
| 4 | Final step | As soon as the falling edge is captured at the Echo pin, the microcontroller reads the count of the Timer. This time count is used to calculate the distance to an object. |
| 5 | Exit | After that click on Create Action |

* When a pulse of 10µsec or more is given to the Trig pin, 8 pulses of 40 kHz are generated. After this, the Echo pin is made high by the control circuit in the module.
* When a pulse of 10µsec or more is given to the Trig pin, 8 pulses of 40 kHz are generated. After this, the Echo pin is made high by the control circuit in the module.
