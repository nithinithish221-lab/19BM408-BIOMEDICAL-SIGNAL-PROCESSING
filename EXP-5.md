# DESIGN OF DIGITAL BUTTERWORTH LOW PASS FILTER USING BILINEAR TRANSFORMATION
# Aim:

To design a digital Butterworth low pass filter using the bilinear transformation method in MATLAB satisfying the given constraints:

0.707≤∣H(ω)∣≤1.0;0≤ω≤0.2π

∣H(ω)∣≤0.08;0.4π≤ω≤π

Assume sampling period T=1second.

# APPARATUS REQUIRED :
MATLAB software
Computer system

Given Specifications

Passband edge frequency:

ω_p=0.2π

Stopband edge frequency:

ω_s=0.4π

Passband ripple:

A_p=-20〖log⁡〗_10 (0.707)=3" dB"

Stopband attenuation:

A_s=-20〖log⁡〗_10 (0.08)≈21.94" dB"

Sampling period:

T=1" second"

# THEORY :
The Butterworth filter is a maximally flat magnitude filter with no ripples in the passband and stopband.
The bilinear transformation converts an analog filter into a digital filter using the relation:

s=2/T  (1-z^(-1))/(1+z^(-1) )

Frequency pre-warping is done to compensate for frequency distortion introduced by bilinear transformation.
The steps involved are:

1)Prewarp digital frequencies to analog frequencies.  

2)Design analog Butterworth filter.
  
3)Convert analog filter into digital filter using bilinear transformation.
  
4)Plot magnitude and phase response.

# ALGORITHM :

1.	Specify passband and stopband edge frequencies.
2.	Convert digital frequencies to analog frequencies using pre-warping.
3.	Compute filter order and cutoff frequency using Butterworth approximation.
4.	Design analog Butterworth low pass filter.
5.	Convert analog filter into digital filter using bilinear transformation.
6.	Plot frequency response using freqz.
7.	Verify whether the filter satisfies the given constraints.

# MATLAB CODE :
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/e48214a0-98c7-47be-9f73-2ba155312d5f" />
<img width="1079" height="438" alt="image" src="https://github.com/user-attachments/assets/cd66b941-8691-41ab-aff3-14188f690128" />

# OUTPUT GRAPH :
<img width="849" height="1480" alt="image" src="https://github.com/user-attachments/assets/aace277a-0be0-4dca-aa72-cd6bbcd410c4" />

# RESULT:
A digital Butterworth low pass filter satisfying the given constraints was successfully designed using the bilinear transformation method and its frequency response was verified using MATLAB.



