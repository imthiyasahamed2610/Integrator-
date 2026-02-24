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
<img width="1037" height="605" alt="image" src="https://github.com/user-attachments/assets/16dbcfe6-86fe-4016-9aec-4f1c0ddaea1f" />

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
<img width="1022" height="341" alt="image" src="https://github.com/user-attachments/assets/8018aa8a-2972-4f5c-ad99-b6cbf7e9f027" />

## Waveforms
<img width="1031" height="640" alt="image" src="https://github.com/user-attachments/assets/4e61120f-9785-497e-b59e-ccefb961337b" />
![WhatsApp Image 2026-02-23 at 9 46 16 AM](https://github.com/user-attachments/assets/bc27273a-b6c0-4b3a-9f2d-0f59b8fa055e)
![WhatsApp Image 2026-02-23 at 9 46 16 AM](https://github.com/user-attachments/assets/ec149995-e13a-4676-9343-a2a002a054ae)

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

An integrator is an op-amp circuit that produces an output voltage proportional to the integral of the input voltage.

2.	Write the output equation of integrator.

Vout = - (1 / RC) ∫ Vin dt

Where:
R = Resistor
C = Capacitor
Vin = Input voltage

3.	Why does output lag input?

The output lags input by 90° because integration of a sine wave produces a cosine wave which lags the input signal

4.	What happens at very low frequency?

At very low frequency, the output voltage increases and may cause saturation.

5.	What is practical integrator?

   A practical integrator is a modified integrator circuit that includes additional resistor to improve stability and prevent saturation.
