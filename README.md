## Experiment No: 4
INTEGRATOR USING OP-AMP (μA741)
## Aim
To design and simulate an Integrator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the integral of the input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R = 10 kΩ
•	Capacitor Cf = 0.01 µF
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1179" height="716" alt="image" src="https://github.com/user-attachments/assets/04a59be3-5f91-4823-90ca-05eb37822d69" />
## Connection Details:
•	Input signal → Resistor (R) → Inverting terminal (Pin 2)
•	Feedback capacitor (Cf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
An Integrator circuit produces an output voltage proportional to the integral of the input voltage.
## Working Principle:
•	When input is constant → output is ramp signal
•	Output is inverted
•	Output depends on time
For Sine Wave Input:
•	Output lags input by 90°
•	Output amplitude decreases with frequency
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistor, capacitor, signal generator, and CRO.
3.	Connect circuit in integrator configuration.
4.	Apply ±15V power supply.
5.	Set input waveform (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
S.No	           Input Signal	 Frequency	      Expected Output	               Practical Observation
<img width="959" height="397" alt="image" src="https://github.com/user-attachments/assets/a4b9ac51-a799-40be-b3ee-a34bdba8cb90" />

## Waveforms
<img width="1380" height="858" alt="image" src="https://github.com/user-attachments/assets/e20a65e1-3d65-41e4-9154-b05d61f83c7e" 
## Result
The Integrator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the integral of the input signal.
The circuit behaves as an integrator.
## Conclusion
•	Output lags input by 90° (for sine input).
•	Output amplitude decreases with increase in frequency.
•	Used in waveform generation and analog computation.
## Viva Questions
1.	What is an integrator circuit?
2.	Write the output equation of integrator.
3.	Why does output lag input?
4.	What happens at very low frequency?
5.	What is practical integrator?
