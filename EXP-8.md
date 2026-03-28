# HAMMING WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Hamming Window and study its frequency characteristics.
# THEORY:

Hamming window is defined as:

w(n)=0.54-0.46cos⁡(2πn/N)

Characteristics:
Reduced side lobes

Better stopband attenuation (~41 dB)

Slightly wider main lobe than rectangular

Reduced ripple

Design Equation:

h(n)=h_d (n)⋅w(n)

Where hd(n) is ideal impulse response.

# ALGORITHM:
1.	Choose N and ωc
2.	Compute ideal impulse response
3.	Generate Hamming window
4.	Multiply and obtain h(n)
5.	Plot magnitude & phase

# MATLAB CODE :
<img width="1079" height="965" alt="image" src="https://github.com/user-attachments/assets/bf77b2d8-a425-4cfe-b952-856dc0a3f4f0" />

# OUTPUT GRAPH :
<img width="922" height="1599" alt="image" src="https://github.com/user-attachments/assets/c7825bf8-ad64-4d9e-9446-5623bd7808bd" />

# RESULT :
The FIR filter was designed using Hamming window .

