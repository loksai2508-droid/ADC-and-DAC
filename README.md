## Experiment 7 (a): Analog to Digital Converter (ADC) using Proteus
## Aim
To design and simulate an Analog to Digital Converter (ADC) circuit using Proteus and observe the conversion of an analog input voltage into its equivalent digital output.
## Apparatus / Software Required
•	Proteus Design Suite
•	ADC IC (ADC0804)
•	Resistors
•	Capacitor
•	Potentiometer (for analog input)
•	Clock components
•	LED display / Logic probe
•	Power supply (5V)
## Theory
An Analog to Digital Converter (ADC) converts a continuous analog signal into a digital representation. ADCs are widely used in digital systems where analog signals from sensors need to be processed by microcontrollers or computers.
The ADC0804 is an 8-bit ADC that uses the successive approximation technique for conversion. It converts the analog input voltage into an equivalent 8-bit binary number.
Important Features
•	Resolution: 8-bit
•	Input voltage range: 0–5 V
•	Conversion method: Successive approximation
•	Output: Digital binary (D0–D7)
The digital output is proportional to the input analog voltage.
## Circuit Diagram
Design the circuit in Proteus using ADC0804 with:
•	Analog input from potentiometer
•	Clock using resistor and capacitor
•	Output connected to LEDs or logic probes
## Procedure
1.	Open Proteus Design Suite.
2.	Select the following components from the library:
o	ADC0804
o	Resistor
o	Capacitor
o	Potentiometer
o	LEDs
3.	Connect the analog input pin (VIN+) to the potentiometer.
4.	Connect VIN− to ground.
5.	Create the clock using resistor and capacitor between CLK pins.
6.	Connect output pins D0–D7 to LEDs.
7.	Apply 5V supply to the ADC.
8.	Run the simulation.
9.	Vary the potentiometer and observe the digital output.

## Tabulation

## Result
The Analog to Digital Converter circuit was successfully designed and simulated in Proteus, and the analog input voltage was converted into the corresponding digital output.

## Experiment 7(b): Digital to Analog Converter (DAC) using Proteus
## Aim
To design and simulate a Digital to Analog Converter (DAC) circuit using Proteus and observe the conversion of digital signals into analog output voltage.
## Apparatus / Software Required
•	Proteus Design Suite
•	DAC IC (DAC0808)
•	Resistors
•	Operational Amplifier (e.g., µA741)
•	Digital input switches
•	Power supply
## Theory
A Digital to Analog Converter (DAC) converts digital binary data into an equivalent analog voltage or current.
The DAC0808 is an 8-bit DAC that produces an analog current proportional to the digital input. An operational amplifier is used to convert the output current into a voltage signal.
Features
•	8-bit resolution
•	Fast conversion
•	Compatible with digital systems
The analog output voltage depends on the digital input combination.
## Circuit Diagram
Design the circuit in Proteus using DAC0808 with:
•	8 digital switches for binary input
•	Op-Amp for current to voltage conversion
•	Output connected to voltmeter
## Procedure
1.	Open Proteus software.
2.	Select components:
o	DAC0808
o	Operational amplifier (741)
o	Resistors
o	Digital switches
3.	Connect binary inputs (D0–D7) using switches.
4.	Connect DAC output to the op-amp circuit.
5.	Connect a voltmeter at the output.
6.	Run the simulation.
7.	Change digital input combinations and observe the output voltage.

## Tabulation

## Result
The Digital to Analog Converter circuit was successfully designed and simulated in Proteus, and the digital input was converted into corresponding analog voltage.

## Applications of ADC and DAC
•	Data acquisition systems
•	Digital signal processing
•	Microcontroller interfacing
•	Audio and video processing
•	Instrumentation systems
