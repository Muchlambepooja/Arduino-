# Arduino-
This repository presents  the design of Arduino Board .The boards are equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards ('shields') or breadboards (for prototyping) and other circuits. The boards feature serial communications interfaces, we need to use external  Universal Serial Bus (USB) on some models, which are also used for loading programs . The below figure shows the power module of arduino board using eagle tool.
![power module](https://user-images.githubusercontent.com/91477166/134933617-c281e0b7-52b0-430e-a4fc-98a04329524c.PNG)


This Power Module Consist of Voltage Regulator, Power_jackpth_lock, 2-Capacitors and vcc.with Input voltage 7V to 16V .


VOLTAGE REGULATOR:
A voltage regulator is a system designed to automatically maintain a constant voltage. A voltage regulator may use a simple feed-forward design or may include negative feedback. It may use an electromechanical mechanism, or electronic components. Depending on the design, it may be used to regulate one or more AC or DC voltages.
Electronic voltage regulators are found in devices such as computer power supplies where they stabilize the DC voltages used by the processor and other elements. In automobile alternators and central power station generator plants, voltage regulators control the output of the plant. In an electric power distribution system, voltage regulators may be installed at a substation or along distribution lines so that all customers receive steady voltage independent of how much power is drawn from the line.


POWER_JACKPTH_LOCK:
Power circuit wired up
Whenever a net splits in two directions a junction node is created. This signifies that all three intersecting nets are connected. If two nets cross, but there's not a junction, those nets are not connected.


CAPACITORS;
A capacitor is a device that stores electrical energy in an electric field. It is a passive electronic component with two terminals.
The effect of a capacitor is known as capacitance. While some capacitance exists between any two electrical conductors in proximity in a circuit, a capacitor is a component designed to add capacitance to a circuit. The capacitor was originally known as a condenser or condensator.This name and its cognates are still widely used in many languages, but rarely in English, one notable exception being condenser microphones, also called capacitor microphones.


MICROCONTROLLER:

![Untitled MICRO](https://user-images.githubusercontent.com/91477166/134943802-9d5f9fb5-34e9-4055-a048-e4feaa09a2d5.PNG)

ATmega328P is a high performance yet low power consumption 8-bit AVR microcontroller that’s able to achieve the most single clock cycle execution of 131 powerful instructions thanks to its advanced RISC architecture. It can commonly be found as a processor in Arduino boards such as Arduino Fio and Arduino Uno.

Features and Parametrics


Features:
High endurance non-volatile memory segments


In system self-programmable flash program memory
Programming Lock for software security


Peripheral features


Two 8-bit Timer/Counter with separate prescaler, compare mode.
One 16-bit Timer/Counter with separate prescaler, compare mode, and capture mode


Temperature measurement


Programmable serial USART and watchdog timer with separate on-chip oscillator


Unique features compared to other microcontrollers (ARM, 8051, PIC):


Power-on reset and programmable brown-out detection
Internal calibrated oscillator
External and Internal interrupt sources


Six sleep modes: Idle, ADC noise reduction, power-save, power-down, standby, and extended standby


Parametrics:


Program Memory Type:	Flash

Program Memory Size:	32

CPU Speed (MIPS/DMIPS)	20

SRAM (KB)	2,048

Data EEPROM/HEF (bytes)	1,024

Digital Communication Peripheral	1-UART, 2-SPI, 1-I2C

Capture/Compare/PWM Peripheral	1 Input Capture, 1 CCP, 6PWM

Timers/Counters	2 x 8-bit, 1x 16 bit

Number of Comparators	1

Temperature Range	: -40 to 85deg

Operating Voltage Range (V)	1.8 to 5.5V

Pin Count	: 32

Low Power:	Yes


Advantages and Disadvantages:


Advantages:

Processors are simpler to use, with the usage of 8bit and 16bit instead of 32/64bit which are more complex
Readily usable without additional computing components with 32k bytes of onboard self-programmable flash program memory as well as 23 programmable I/O lines
Code Efficient, all 31 registers are directly connected to the arithmetic logic unit (ALU), making it 10 times faster than conventional CISC microcontrollers
Optimized for AVR enhanced RISC instruction set.


Disadvantages:

Lacks performance compared to higher bit microcontrollers
Product Applications
The ATmega328P is supported with a full suite of program and system development tools which includes: C compilers, macro assemblers, program debugger/simulators, in-circuit emulators, and evaluation kits.

The fast PWM mode that provides a high-frequency PWM waveform generation allows for it to be suited for power regulation, rectification, and DAC applications.

We have also used Header Pins as shown below

![abcd](https://user-images.githubusercontent.com/91477166/134953086-77eabae7-3045-4bdb-ab8c-5c033848843d.png)

The Arduino project began in 2005 as a tool for students at the Interaction Design Institute Ivrea, Italy, aiming to provide a low-cost and easy way for novices and professionals to create devices that interact with their environment using sensors and actuators. Common examples of such devices intended for beginner hobbyists include simple robots, thermostats and motion detectors.

Schematic To Board:








