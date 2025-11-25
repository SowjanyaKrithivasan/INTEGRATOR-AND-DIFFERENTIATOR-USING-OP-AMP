# DESIGN OF INTEGRATOR-AND-DIFFERENTIATOR-USING-OP-AMP
# AIM: 
To design and test the performance of integrator and differentiator circuits using Op-amp 741.

# APPARATUS REQUIRED:
<img width="992" height="272" alt="image" src="https://github.com/user-attachments/assets/d8b53c15-71e0-4acf-9611-92083a57e93a" />

# THEORY:
# INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
                Vo = -(1/Rf C1 )∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
                  T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.



# INTEGRATOR CIRCUIT DIAGRAM
<img width="446" height="270" alt="image" src="https://github.com/user-attachments/assets/521ab839-8846-49d0-bc6d-d8b2105934f3" />

# MODEL GRAPH:
# i) SINE WAVE INPUT:
<img width="353" height="243" alt="image" src="https://github.com/user-attachments/assets/a9639775-1bfb-4cab-99c4-3d66e7dd5907" />

# ii) SQUARE WAVE INPUT
<img width="678" height="358" alt="image" src="https://github.com/user-attachments/assets/3a9d9a97-3057-49e5-8622-3d4862b8a053" />

# TABULATION:

![WhatsApp Image 2025-11-25 at 19 44 32_0b537df4](https://github.com/user-attachments/assets/47f33310-9618-49a7-8c80-675f9e05c55f)



# THEORY:
# DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
                                          Vo = -Rf C1(dVi/dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:

1. Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 μF, calculate the value of Rf.
2. Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.
The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

# DIFFERENTIATOR CIRCUIT DIAGRAM
<img width="485" height="264" alt="image" src="https://github.com/user-attachments/assets/f5242bb4-723a-447c-85a9-02798491222b" />

# MODEL GRAPH:
# i) SINE WAVE INPUT:
<img width="635" height="306" alt="image" src="https://github.com/user-attachments/assets/5c0d742f-20fe-45d7-8cb3-d065c98dd595" />

# ii) SQUARE WAVE INPUT
<img width="614" height="285" alt="image" src="https://github.com/user-attachments/assets/af0e1a53-56c7-4af2-a5a4-859c7c2e842e" />


# TABULATION:

![WhatsApp Image 2025-11-25 at 19 45 05_3947cfb2](https://github.com/user-attachments/assets/ba7a5d5c-0d0f-4afb-b1e9-a2d5b3ba466a)


# PROCEDURE:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.

# INTEGRATOR GRAPH:

![WhatsApp Image 2025-11-25 at 19 45 34_8dde7cbd](https://github.com/user-attachments/assets/fb17de0f-62c9-40ed-b153-9a56d14e1651)


# DIFFERENTIATOR GRAPH:

![WhatsApp Image 2025-11-25 at 19 46 33_3a1961be](https://github.com/user-attachments/assets/12406af4-7e9c-4c5c-9dc4-09aa4e58ef06)



# RESULT:

Thus an Integrator and Differentiator using op-amp are designed and their 
performance was successfully tested using op-amp IC 741.





