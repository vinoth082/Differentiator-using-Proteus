## Experiment No: 3
DIFFERENTIATOR USING OP-AMP (μA741)
## Aim
To design and simulate a Differentiator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the rate of change of input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Capacitor C = 0.01 µF
•	Resistor Rf = 10 kΩ
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1052" height="637" alt="image" src="https://github.com/user-attachments/assets/9669d5fc-7d60-454a-8ef3-fd1d644e83a2" />

## Connection Details:
•	Input signal → Capacitor (C) → Inverting terminal (Pin 2)
•	Feedback resistor (Rf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Differentiator circuit produces an output voltage proportional to the rate of change of input voltage.
## Working Principle:
•	When input changes rapidly → output amplitude increases
•	When input is constant → output is zero
•	Output is inverted
## Procedure
1.	Open Proteus software.
2.	Select μA741, capacitor, resistor, signal generator, and CRO.
3.	Connect circuit in differentiator configuration.
4.	Apply ±15V power supply.
5.	Set input sine wave (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
S.No 	         Input Signal	              Frequency	            Expected  Output	            Practical Observation

## Waveforms
<img width="1600" height="997" alt="image" src="https://github.com/user-attachments/assets/2c62dc5f-1cf9-463b-bb04-26f507e9daf3" />

•	Sine input → Cosine output (90° phase shift)
•	Square input → Positive & negative spikes
•	Triangular input → Square wave
## Result
The Differentiator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the rate of change of input voltage.
The circuit behaves as a differentiator.
## Conclusion
•	Output depends on frequency.
•	Output leads input by 90° (for sine input).
•	Higher frequency → Higher output amplitude.
•	Used in wave shaping and signal processing applications.
## Viva Questions
1.	What is a differentiator?
<img width="1090" height="135" alt="image" src="https://github.com/user-attachments/assets/87043eeb-f6c5-4d6b-a5c6-c65be43686e3" />

2.	Write the output equation of differentiator.
<img width="825" height="291" alt="image" src="https://github.com/user-attachments/assets/0f3bcc0e-a4f5-46f6-a006-4d99e7d30d3e" />

3.	Why is output leading input?
<img width="992" height="105" alt="image" src="https://github.com/user-attachments/assets/d920a718-71f2-4c17-a2e0-f81ceb149c55" />

4.	What happens at very high frequency?
<img width="837" height="191" alt="image" src="https://github.com/user-attachments/assets/8a49481b-74f2-4e2b-8547-bd71baa0e3fa" />

5.	What is practical differentiator?
<img width="850" height="167" alt="image" src="https://github.com/user-attachments/assets/397dfdcb-37d7-4567-937d-5cc73ebb9ad5" />

