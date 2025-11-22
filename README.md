# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---
           
 
         
		 
		 
		 
## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
<img width="836" height="455" alt="image" src="https://github.com/user-attachments/assets/e5181151-836f-4f80-8f56-53b23ff05c74" />


## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

| S.No | Frequency (Hz) | Output Voltage (V) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|--------------------|-----------------------------|
| 1    |   300             |     1.6               |           4.08                  |
| 2    |   400            |      1.6              |             4.08                |
| 3    |   500              |    1.6                |           4.08                  |
| 4    |   600             |     1.6               |            4.08                 |
| 5    |   700             |     1.6               |            4.08                 |
| 6    |   900             |     1.6               |            4.08                 |
| 7    |   1             |       1.5             |              3.52               |
| 8    |   1.5             |     1.2               |            1.58                 |
| 9    |   2             |       600             |              -4.4               |
| 10   |   2.5             |    380                |             -8.4                |
| 11   |   3             |      260              |               -11.70              |

		

---

## OUT PUT WAVEFORM AND DISCUSSION 

---
<img width="1280" height="1009" alt="image" src="https://github.com/user-attachments/assets/1401159d-9bc8-4d92-9527-970b5a75c811" />

<img width="950" height="662" alt="ss lps cir" src="https://github.com/user-attachments/assets/f04342f0-0f6a-4b43-9254-c3b93fab5174" />

<img width="1915" height="459" alt="ss lpf op" src="https://github.com/user-attachments/assets/cc78c38f-8585-416a-a37f-660a023fe126" />

 
 
 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

<img width="887" height="486" alt="image" src="https://github.com/user-attachments/assets/907a1395-28d4-406f-ac09-96c4e060587e" />


## MODEL GRAPH

<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
| S.No | Frequency (Hz) | Output Voltage (V) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|--------------------|-----------------------------|
| 1    |    300hz            |       140             |          -17.07                   |
| 2    |   400             |         220           |             -13.15                |
| 3    |   500             |         260           |             -11.70                |
| 4    |   600             |         320           |             -9.8                |
| 5    |    700            |         420           |             -7.5                |
| 6    |    800            |        540            |             -5.3                |
| 7    |    900            |       600             |             -4.4                |
| 8    |   1k             |        740            |               -2.6              |
| 9    |   1.2             |       900             |              -0.91               |
| 10   |  1.3              |       1             |                0             |
| 11   |   1.4             |      1.1              |              0               |
| 12   |   1.5             |       1.1             |             0.82                |

---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1280" height="1008" alt="image" src="https://github.com/user-attachments/assets/a077737d-5f26-4d1d-8d07-64d7c5cd1c8b" />

<img width="1129" height="513" alt="ss hpf cir 2 " src="https://github.com/user-attachments/assets/d7424f44-85cc-411f-8ebc-d0a29db972a4" />

<img width="1914" height="475" alt="ss hpf op 2 " src="https://github.com/user-attachments/assets/8869a2cb-5e7d-4220-8190-35961d490ad3" />




---

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

<img width="1068" height="446" alt="image" src="https://github.com/user-attachments/assets/ee37b95a-05ea-448c-9102-111e071e41e8" />

## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
| S.No | Frequency (Hz) | Output Voltage (V) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|--------------------|-----------------------------|
| 1    |        40        |     0.1               |          -20                   |
| 2    |       60         |     1               |             0                |
| 3    |       80         |     1.2               |           1.5                  |
| 4    |      100          |     1.4               |          2.9                   |
| 5    |     125           |    1.6                |          4.08                   |
| 6    |     150           |     1.8               |          5.1                   |
| 7    |     175           |     2               |            6                 |
| 8    |     200           |     2.4               |         7.6                    |
| 9    |     250           |     2.4               |          7.6                   |
| 10   |    300            |     2.4               |           7.6                  |
| 11   |    400            |     2.4               |           7.6                  |
| 12   |    450            |     2.4               |           7.6                  |

---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1280" height="997" alt="image" src="https://github.com/user-attachments/assets/6d99ad53-72da-459e-9468-fd66d234b97e" />

<img width="948" height="515" alt="ss bps cir " src="https://github.com/user-attachments/assets/e7eec0a2-9d3e-43dd-905f-223ced0c5874" />

<img width="1893" height="448" alt="ss bpf op" src="https://github.com/user-attachments/assets/b9501192-ae95-45eb-830e-81955fd2aba4" />



---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
