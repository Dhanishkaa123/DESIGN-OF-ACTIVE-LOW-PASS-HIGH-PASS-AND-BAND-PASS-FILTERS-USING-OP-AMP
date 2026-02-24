# DESIGN-OF-ACTIVE-LOW-PASS-HIGH-PASS-AND-BAND-PASS-FILTERS-USING-OP-AMP
# AIM:
To design and obtain the frequency response of
i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

# APPARATUS REQUIRED:
| S.No | Name of the Apparatus        | Range        | Quantity        |
|------|-----------------------------|-------------|-----------------|
| 1    | Function Generator          | 3 MHz       | 1               |
| 2    | DSO                         | 30 MHz      | 1               |
| 3    | Dual RPS                    | (0 – 30) V  | 2               |
| 4    | Op-Amp (µA741)              | —           | 2               |
| 5    | Bread Board                 | —           | 1               |
| 6    | Resistors (1.6K, 10K, 5.86K, 38.8K, 7.9K) | — | — |
| 7    | Connecting wires and probes | As required | —               |

# THEORY:
# LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.

# CIRCUIT DIAGRAM: 
# LOW PASSFILTER
<img width="836" height="455" alt="image" src="https://github.com/user-attachments/assets/3a6330b3-ff28-4790-b944-50914694b1aa" />

# TABULATION:
| S.No | Frequency (Hz) | Output Voltage (Volts) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|------------------------|----------------------------|
| 1    |                |                        |                            |
| 2    |                |                        |                            |
| 3    |                |                        |                            |
| 4    |                |                        |                            |
| 5    |                |                        |                            |
| 6    |                |                        |                            |
| 7    |                |                        |                            |
| 8    |                |                        |                            |
| 9    |                |                        |                            |
| 10   |                |                        |                            |
| 11   |                |                        |                            |
| 12   |                |                        |                            |

# MODEL GRAPH :
<img width="1005" height="488" alt="image" src="https://github.com/user-attachments/assets/04b8a789-725b-498c-909a-24f3d535bdb1" />

# PRACTICAL GRPAH:
PASTE UR GRAPH HERE
# THEORY 
# HIGH PASS FILTER
The frequency at which the magnitude of the gain is 0.707 times the maximum value of gain is called low cut off frequency. Obviously, all frequencies higher than fL are pass band frequencies with the highest frequency determined by the closed –loop band width all of the op- amp.
# CIRCUIT DIAGRAM:
# HIGH PASSFILTER
<img width="888" height="474" alt="image" src="https://github.com/user-attachments/assets/6d46ac56-0e63-434c-b670-627d5ae6b61a" />

# TABULATION:
| S.No | Frequency (Hz) | Output Voltage (Volts) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|------------------------|----------------------------|
| 1    |                |                        |                            |
| 2    |                |                        |                            |
| 3    |                |                        |                            |
| 4    |                |                        |                            |
| 5    |                |                        |                            |
| 6    |                |                        |                            |
| 7    |                |                        |                            |
| 8    |                |                        |                            |
| 9    |                |                        |                            |
| 10   |                |                        |                            |
| 11   |                |                        |                            |
| 12   |                |                        |                            |

# MODEL GRAPH :
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/e5dd4a94-c844-4c4c-889b-7631e30407e6" />


# PRACTICAL GRPAH:
PASTE UR GRAPH HERE
# THEORY 
# BAND PASS FILTER
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > fL. Any input frequency outside this pass band is attenuated. There are two types of band-pass filters. Wide band pass and Narrow band pass filters. We can define a filter as wide band pass if its quality factor Q <10. If Q>10, then we call the filter a narrow band pass filter. A wide band pass filter can be formed by simply cascading high-pass and low-pass sections. The order of band pass filter depends on the order of high pass and low pass sections.

# CIRCUIT DIAGRAM:
# BAND PASS FILTER
<img width="1068" height="446" alt="image" src="https://github.com/user-attachments/assets/69fd757e-29c8-44c2-abf1-9dda78f9ce09" />

# TABULATION:
| S.No | Frequency (Hz) | Output Voltage (Volts) | Gain = 20 log (Vo/Vi) (dB) |
|------|----------------|------------------------|----------------------------|
| 1    |                |                        |                            |
| 2    |                |                        |                            |
| 3    |                |                        |                            |
| 4    |                |                        |                            |
| 5    |                |                        |                            |
| 6    |                |                        |                            |
| 7    |                |                        |                            |
| 8    |                |                        |                            |
| 9    |                |                        |                            |
| 10   |                |                        |                            |
| 11   |                |                        |                            |
| 12   |                |                        |                            |

# MODEL GRAPH :
<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/1b24ba4f-6fd5-4e79-96c7-5a913eff0217" />

# PRACTICAL GRPAH:
PASTE UR GRAPH HERE

# PROCEDURE - (LPF & HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.

# PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.

# RESULT:
Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
