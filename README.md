High Voltage High Frequency Power Supply (HVHFPS) Design and Simulation

This project involves the design, simulation, and experimental validation of a High Voltage High Frequency Power Supply system, developed at the Pulsed Power and Electromagnetics Division of Bhabha Atomic Research Center, Visakhapatnam. 
The power supply delivers high-voltage outputs (up to 10 kV) at high frequencies (up to 25 kHz), suitable for applications such as gas ionization, plasma generation, and medical X-ray signal generation.

Key components include:

Full-Bridge H-Bridge Inverter using MOSFETs: Converts DC input into high-frequency AC output, controlled via PWM.

PWM Generation using NE555 Timer IC: Configured in astable mode to generate precise PWM signals with adjustable frequency and duty cycle.

IR2110 MOSFET Driver IC: Facilitates robust and isolated driving of high-side and low-side MOSFETs, using bootstrap capacitors for high-side gate voltage supply.

Control and Protection Circuitry: For regulating output voltage and ensuring reliable, safe operation.

Simulations using LTspice demonstrate the generation of complementary PWM signals and proper switching of MOSFETs to achieve the desired AC output waveform. The design aims for high efficiency, compactness, and stability, with future enhancements planned to reduce noise and increase voltage output.

