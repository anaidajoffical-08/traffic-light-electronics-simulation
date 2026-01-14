# traffic-light-electronics-simulation
-Project Description

This project implements a traffic light control system using digital logic ICs simulated in Tinkercad Circuits, without using any microcontroller.
A function generator is used as the clock source to provide periodic timing pulses, while a DC power supply powers the circuit. The timing pulses drive a 74HC74 D flip-flop, which is configured to generate sequential logic states. A 74HC02 NOR gate IC is used to perform the required logic operations for controlling the output states.
Based on the clock signal, the outputs change sequentially, causing the red, yellow, and green LEDs to turn ON and OFF in a fixed order, simulating the operation of a real-world traffic light system.

-The circuit demonstrates:
Sequential logic operation
Clock-driven state changes
Practical use of flip-flops and logic gates
Hardware-based traffic light control without software
Components Used
Function Generator (clock input)
DC Power Supply
74HC74 (D Flip-Flop)
74HC02 (NOR Gate)
LEDs (Red, Yellow, Green)
Resistors
Breadboard and connecting wires

-Working Principle 
The function generator provides a periodic clock signal to the flip-flop. Each clock pulse changes the output state of the flip-flop. These states are processed through NOR gate logic to ensure that only one LED is active at a time. As a result, the LEDs switch sequentially, accurately representing traffic light operation.
