# 4-Stage-Amplifier
A 4-stage precision analog signal chain designed in LTSpice. Features differential amplification, lowpass filtering, multi-step variable gain and precision rectification using the ADA4077 high-precision op-amp.


The system was designed in LTSpice and physically prototyped using an ADALM module and Scopy for real-time analysis.

The signal chain is optimized for the ADA4077 high-precision op-amp, consisting of the following stages:

* `Stage 1:` Differential Amplifier with fixed Linear Gain of 5.
* `Stage 2:` 2nd-Order Low-Pass Sallen-Key Filter with a Butterworth response.
* `Stage 3:` Programmable Gain Amplifier (PGA) providing four gain steps ranging from 8dB to 14dB.
* `Stage 4:` Full-Wave Precision Rectifier.


Full theoretical derivation, simulation plots, and photos of the physical circuit on the breadboard can be found in the `PROIECT LA DISCIPLINA SCIA.pdf` file. 
