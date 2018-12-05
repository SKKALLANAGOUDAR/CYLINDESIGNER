``# Gathering pertinent information:
### 1.What kind of sources are to be searched?
#### The searched sources include YouTube ,online sites , Internet , Wikipedia.

### 2.  What are the existing solutions for the problem?
#### The existing solutions include:
#### Drawing the patterns manually.
#### Use  of Complex machines.
#### Use of automated ,user-friendly robots.

### 3. Have u gone through any   DIY projects?
### 4. What are the components and sub- components do you feel are needed for your project?
#### The components include:
### Stepper Motor:
#### The operation of this motor works on the principle that unlike poles attract each other and like poles repel each other. When the stator windings are excited with a DC supply, it produces magnetic flux and establishes the North and South poles. 
![](https://user-images.githubusercontent.com/42512399/49539336-6af54380-f8f3-11e8-9e57-a27e87494481.png)
### DC motor:
#### The DC motor works over a fair range of voltage. The higher the input voltage more is the RPM (rotations per minute) of the motor. For example, if the motor works in the range of 6-12V, it will have the least RPM at 6V and maximum at 12 V.
#### In terms of voltage, we can put the equation as:
#### RPM= K1 * V, where,
#### K1= induced voltage constant
#### V=voltage applied
![](https://user-images.githubusercontent.com/42512399/49539494-c7586300-f8f3-11e8-90e3-c1603b41fe3f.png)
### Arduino mega: 
An Arduino is actually a microcontroller-based kit which can be either used directly by purchasing from the vendor or can be made at home using the components, owing to its open source hardware feature. It is basically used in communications and in controlling or operating many devices. It was founded by Massimo Banzi and David Cuartillas in 2005.
Arduino Architecture:
Arduino’s processor basically uses the Harvard architecture where the program code and program data have separate memory. It consists of two memories- Program memory and the data memory. The code is stored in the flash program memory, whereas the data is stored in the data memory. The Atmega328 has 32 KB of flash memory for storing code (of which 0.5 KB is used for the bootloader), 2 KB of SRAM and 1 KB of EEPROM and operates with a clock speed of 16MHz.
![](https://user-images.githubusercontent.com/42512399/49539597-fe2e7900-f8f3-11e8-91ce-7d0fab7ef2b9.png)
### Bread board:
Bread Board is a great tool to design and test your circuits. You do not need to solder wires and components to make a circuit while using a bread board. It is easier to mount components & reuse them. Since, components are not soldered you can change your circuit design at any point without any hassle.

Structure of a Bread Board: Basically, a bread board is an array of conductive metal clips encased in a box made of white ABS plastic, where each clip is insulated with another clips. There are a number of holes on the plastic box, arranged in a particular fashion. A typical bread board layout consists of two types of region also called strips. Bus strips and socket strips. Bus strips are usually used to provide power supply to the circuit. It consists of two columns, one for power voltage and other for ground.
Socket strips are used to hold most of the components in a circuit. Generally it consists of two sections each with 5 rows and 64 columns. Every column is electrically connected from
inside. 
![](https://user-images.githubusercontent.com/42512399/49539660-32a23500-f8f4-11e8-8cbb-53d775a47065.png)
### Driver- L298n: 
The L298N is a dual H-Bridge motor driver which allows speed and direction control of two DC motors at the same time. The module can drive DC motors that have voltages between 5 and 35V, with a peak current up to 2A.


This depends on the voltage used at the motors VCC. The module have an onboard 5V regulator which is either enabled or disabled using a jumper. If the motor supply voltage is up to 12V we can enable the 5V regulator and the 5V pin can be used as output, for example for powering our Arduino board. But if the motor voltage is greater than 12V we must disconnect the jumper because those voltages will cause damage to the onboard 5V regulator. In this case the 5V pin will be used as input as we need connect it to a 5V power supply in order the IC to work properly.
![](https://user-images.githubusercontent.com/42512399/49539820-89a80a00-f8f4-11e8-96c5-35e1a36de3a0.jpg)
### Two channel Relay Module:
  The Arduino Relay module allows a wide range of microcontroller such as Arduino, AVR ,PIC, ARM with digital outputs to control larger loads and devices like AC or DC Motors, electromagnets, solenoids, and incandescent light bulbs. This module is designed to be integrated with 2 relays that it is capable of control 2 relays.The relay shield use one QIANJI JQC-3F high-quality relay with rated load 7A/240VAC,10A/125VAC,10A/28VDC.The relay output state is individually indicated by a light-emitting diode.
![](https://user-images.githubusercontent.com/42512399/49539897-b8be7b80-f8f4-11e8-9fe9-f43ea89bde81.png)
### 12V adapter: 
AC adapters are used with electrical devices that require power but do not contain internal components to derive the required voltage and power from mains power. The internal circuitry of an external power supply is very similar to the design that would be used for a built-in or internal supply.
![](https://user-images.githubusercontent.com/42512399/49540010-02a76180-f8f5-11e8-98e7-eb3393a51bae.png)
Timing belt:
 A timing belt is a non-slipping mechanical drive belt.
![](https://user-images.githubusercontent.com/42512399/49540082-2bc7f200-f8f5-11e8-96da-2af9e957fc1f.png)                                          
### Pulley:
A pulley is a wheel on an axle or shaft that is designed to support movement and change of direction of a taut cable or belt, or transfer of power between the shaft and cable or belt. In the case of a pulley supported by a frame or shell that does not transfer power to a shaft, but is used to guide the cable or exert a force, the supporting shell is called a block, and the pulley may be called a sheave.
A pulley may have a groove or grooves between flanges around its circumference to locate the cable or belt. The drive element of a pulley system can be a rope, cable, belt, or chain.
![](https://user-images.githubusercontent.com/42512399/49540161-5c0f9080-f8f5-11e8-986c-52bb86a8de3f.png)
### Jumper wires:
Jumper wires are simply wires that have connector pins at each end, allowing them to be used to connect two points to each other without soldering. Jumper wires are typically used with breadboards and other prototyping tools in order to make it easy to change a circuit as needed. 
Jumper wires typically come in three versions: male-to-male, male-to-female and female-to-female. The difference between each is in the end point of the wire. Male ends have a pin protruding and can plug into things, while female ends do not and are used to plug things into. Male-to-male jumper wires are the most common and what you likely will use most often. When connecting two ports on a breadboard, a male-to-male wire is what you’ll need.

![](https://user-images.githubusercontent.com/42512399/49540227-8f521f80-f8f5-11e8-88d0-38c87580234f.png)
