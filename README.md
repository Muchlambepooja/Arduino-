<!--Heading-->
# Arduino-Board
<!--links-->


##  Table of Contents

* [1. Introduction]()

* [2.Power Module](https://user-images.githubusercontent.com/91477166/134933617-c281e0b7-52b0-430e-a4fc-98a04329524c.PNG)

* [3. Voltage Regulator](https://user-images.githubusercontent.com/91477166/137732301-d14b79bf-847d-4a53-ac1d-5a26da9be1a0.jpg)

* [4. Power_jackpth_lock](https://user-images.githubusercontent.com/91477166/137733125-0d70d7f8-92f7-4a11-a70f-299146b748ae.png)

* [5. Capacitor](https://user-images.githubusercontent.com/91477166/137733573-614a9385-2981-4580-8750-bcf8b14b4d77.jpg)

* [6. Microcontroller](https://user-images.githubusercontent.com/91477166/134943802-9d5f9fb5-34e9-4055-a048-e4feaa09a2d5.PNG)

* [7. Schematic](https://user-images.githubusercontent.com/91477166/134953086-77eabae7-3045-4bdb-ab8c-5c033848843d.png)

* [8. Board](https://user-images.githubusercontent.com/91477166/134954367-aeb1af29-25dc-444c-b872-aa8de7bfb5b1.png)

* [9. Top Layer](https://user-images.githubusercontent.com/91477166/134954817-afc4833a-c6b3-4553-b30f-944d2f450a21.png)

* [10. Bottom Layer](https://user-images.githubusercontent.com/91477166/134955356-d5f6bea5-aa2f-4f7f-b24b-226915f9a1c8.png)

* [11. Future Scope]()

* [12. Contributors]()
 

<!---links-->


# Introduction :
This repository presents  the design of Arduino Board .The boards are equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards ('shields') or breadboards (for prototyping) and other circuits. The boards feature serial communications interfaces, we need to use external  Universal Serial Bus (USB) on some models, which are also used for loading programs . 

The below figure shows the power module of arduino board using eagle tool.


# Power Module


![power module](https://user-images.githubusercontent.com/91477166/134933617-c281e0b7-52b0-430e-a4fc-98a04329524c.PNG)


This Power Module Consist of Voltage Regulator, Power_jackpth_lock, 2-Capacitors and vcc.with Input voltage 7V to 16V .


##  Voltage Regulator:
A voltage regulator is a system designed to automatically maintain a constant voltage. A voltage regulator may use a simple feed-forward design or may include negative feedback. It may use an electromechanical mechanism, or electronic components. Depending on the design, it may be used to regulate one or more AC or DC voltages.
Electronic voltage regulators are found in devices such as computer power supplies where they stabilize the DC voltages used by the processor and other elements. In automobile alternators and central power station generator plants, voltage regulators control the output of the plant. In an electric power distribution system, voltage regulators may be installed at a substation or along distribution lines so that all customers receive steady voltage independent of how much power is drawn from the line.

![7805-voltage-regulator](https://user-images.githubusercontent.com/91477166/137732301-d14b79bf-847d-4a53-ac1d-5a26da9be1a0.jpg)

##  Power_jackpth_lock:
Power circuit wired up
Whenever a net splits in two directions a junction node is created. This signifies that all three intersecting nets are connected. If two nets cross, but there's not a junction, those nets are not connected.

![Powerjackpath](https://user-images.githubusercontent.com/91477166/137733336-5bc10ee8-a512-4700-b695-84a20960c53e.png)



##  Capacitor:
A capacitor is a device that stores electrical energy in an electric field. It is a passive electronic component with two terminals.
The effect of a capacitor is known as capacitance. While some capacitance exists between any two electrical conductors in proximity in a circuit, a capacitor is a component designed to add capacitance to a circuit. The capacitor was originally known as a condenser or condensator.This name and its cognates are still widely used in many languages, but rarely in English, one notable exception being condenser microphones, also called capacitor microphones.
![download](https://user-images.githubusercontent.com/91477166/137733573-614a9385-2981-4580-8750-bcf8b14b4d77.jpg)


##  Microcontroller:

![Untitled MICRO](https://user-images.githubusercontent.com/91477166/134943802-9d5f9fb5-34e9-4055-a048-e4feaa09a2d5.PNG)

ATmega328P is a high performance yet low power consumption 8-bit AVR microcontroller that???s able to achieve the most single clock cycle execution of 131 powerful instructions thanks to its advanced RISC architecture. It can commonly be found as a processor in Arduino boards such as Arduino Fio and Arduino Uno.

##  Features and Parametrics


### Features:
High endurance non-volatile memory segments


In system self-programmable flash program memory
Programming Lock for software security


###  Peripheral feature:


Two 8-bit Timer/Counter with separate prescaler, compare mode.
One 16-bit Timer/Counter with separate prescaler, compare mode, and capture mode


###   Temperature measurement:


Programmable serial USART and watchdog timer with separate on-chip oscillator


Unique features compared to other microcontrollers (ARM, 8051, PIC):


Power-on reset and programmable brown-out detection
Internal calibrated oscillator
External and Internal interrupt sources


Six sleep modes: Idle, ADC noise reduction, power-save, power-down, standby, and extended standby


###  Parametrics:


Program Memory Type:	Flash

Program Memory Size:	32

CPU Speed (MIPS/DMIPS) :	20

SRAM (KB)	:2,048

Data EEPROM/HEF (bytes)	1,024

Digital Communication Peripheral :	1-UART, 2-SPI, 1-I2C

Capture/Compare/PWM Peripheral :	1 Input Capture, 1 CCP, 6PWM

Number of Comparators :	1

Temperature Range	: -40 to 85deg

Operating Voltage Range (V) :	1.8 to 5.5V

Pin Count	: 28

Low Power:	Yes


###  Advantages and Disadvantages:


####  Advantages:

Processors are simpler to use, with the usage of 8bit and 16bit instead of 32/64bit which are more complex
Readily usable without additional computing components with 32k bytes of onboard self-programmable flash program memory as well as 23 programmable I/O lines
Code Efficient, all 31 registers are directly connected to the arithmetic logic unit (ALU), making it 10 times faster than conventional CISC microcontrollers
Optimized for AVR enhanced RISC instruction set.


#### Disadvantages:

Lacks performance compared to higher bit microcontrollers
Product Applications
The ATmega328P is supported with a full suite of program and system development tools which includes: C compilers, macro assemblers, program debugger/simulators, in-circuit emulators, and evaluation kits.

The fast PWM mode that provides a high-frequency PWM waveform generation allows for it to be suited for power regulation, rectification, and DAC applications.

We have also used Header Pins as shown below

# Schematic

![abcd](https://user-images.githubusercontent.com/91477166/134953086-77eabae7-3045-4bdb-ab8c-5c033848843d.png)

The Arduino project began in 2005 as a tool for students at the Interaction Design Institute Ivrea, Italy, aiming to provide a low-cost and easy way for novices and professionals to create devices that interact with their environment using sensors and actuators. Common examples of such devices intended for beginner hobbyists include simple robots, thermostats and motion detectors.


##   Board:


![Board](https://user-images.githubusercontent.com/91477166/134954367-aeb1af29-25dc-444c-b872-aa8de7bfb5b1.png)

##  Top layer:

![Top layer](https://user-images.githubusercontent.com/91477166/134954817-afc4833a-c6b3-4553-b30f-944d2f450a21.png)


##  Bottom Layer:

![Bottom layer](https://user-images.githubusercontent.com/91477166/134955356-d5f6bea5-aa2f-4f7f-b24b-226915f9a1c8.png)


##  Future Scope:

the Arduino platform has done is to take what was once a fragmented and expensive market for robotics and microprocessors and become the major platform, largely by virtue of much lower cost and ease of use, leading to higher volume and popularity, and community support behind it. Arduino has made it simple to program their boards with any computer via USB and simple to integrate with a wide array of sensors and devices.

##  Contributors:


 Muchlambe Pooja ,B.Tech(Electronics and Communication Engineering), Jawaharlal Nehru Technological University, Hyderabad.










