# Project Documentation

## LDR-Based Automatic Illumination System

### 1. Introduction

The LDR-Based Automatic Illumination System is a light-sensitive
electronic circuit designed to automatically control an LED according to
ambient light conditions.

The project was developed in two stages. The circuit was first assembled
and tested on a breadboard. After validating the circuit, the same
circuit concept was implemented as a custom-made PCB using EasyEDA.

### 2. Objectives

1.  Study the operation of a Light Dependent Resistor.
2.  Develop a basic light-sensitive switching circuit.
3.  Use a transistor as a switching element.
4.  Validate the circuit through breadboard prototyping.
5.  Design a custom PCB based on the tested circuit.
6.  Assemble and test the final PCB.

### 3. Components Used

  ------------------------------------------------------------------------
  Component                                 Quantity Specification
  --------------------- ---------------------------- ---------------------
  LDR                                              1 
                                                    

  Transistor                                       1   BC547
                                                

  LED                                              1 
                                          

  Resistor(s)                                      1
                                                     
                                              

  9V Battery                                       1 9V

  Breadboard                                       1 Prototype board

  Jumper wires                           As required ---
  ------------------------------------------------------------------------

### 4. Circuit Description

The LDR is used as the light-sensing element. Its resistance varies with
the intensity of incident light.

The resulting change in the circuit is used to control the transistor.
The transistor functions as a switch for the LED.


### 5. Breadboard Prototype

The circuit was first assembled on a breadboard using the LDR,
transistor, LED, resistor(s), and 9V battery.

The prototype stage allowed the circuit connections and switching
behavior to be checked before committing the design to a PCB.

<img width="411" height="403" alt="image" src="https://github.com/user-attachments/assets/77ed387b-0592-4c08-87ab-541bff0db92c" />

### 6. PCB Development

After testing the breadboard circuit, the design was transferred to a
custom PCB.

The PCB was designed using EasyEDA. The design workflow included
schematic preparation, component placement, trace routing, design
checking, and preparation for fabrication.


### 7. Hardware Assembly

The components were mounted and connected on the custom PCB according to
the finalized circuit design.


### 8. Testing and Results

Testing was performed by changing the ambient light level around the LDR
and observing the LED response.

Final measured observations should be entered below after confirming the
exact behavior:

  Condition              Expected/Observed LED State   Result
  ---------------------- ----------------------------- ----------------------
  Bright ambient light   \OFF\]                   \[Pass/Observation\]
  Low ambient light      \ON\]                   \[Pass/Observation\]


### 10. Learning Outcomes

The project provided practical experience in:

-   Sensor-based circuit design
-   LDR operation
-   Transistor switching
-   Breadboard prototyping
-   Schematic design
-   PCB layout and routing
-   Hardware assembly
-   Circuit testing and troubleshooting

### 11. Future Improvements

Possible improvements include adjustable sensitivity, improved power
efficiency, multiple output channels, microcontroller-based control, and
enclosure design.

### 12. Conclusion

The project demonstrated the complete progression from a basic
electronic circuit prototype to a custom PCB implementation. It provided
hands-on experience in circuit development, PCB design, hardware
assembly, and testing.

### 13. Project Evidence

Attach the following to the final report/repository:

-   Breadboard prototype photograph
-   Circuit schematic
-   EasyEDA PCB layout
-   Fabricated PCB photographs
-   Final working PCB photograph
-   Source/design files where available
