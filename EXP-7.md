# RECTANGULAR WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Rectangular Window and analyze its magnitude and phase response using MATLAB.
# Theory :
Rectangular Window
The Rectangular window is defined as:
        w(n)=1≤n≤N
Characteristics:
Narrowest main lobe

Highest side lobes

High ripple (Gibbs phenomenon)

Sharp transition width

It simply truncates the ideal impulse response.

Design Equations
Ideal Low Pass Impulse Response:

h_d (n)=(sin⁡ω_c (n-α))/(π(n-α))

Where:

α=N/2

Actual filter:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Choose filter order N
2.	Choose cutoff frequency ωc
3.	Generate ideal impulse response
4.	Generate rectangular window
5.	Multiply both
6.	Plot frequency response

# MATLAB CODE :
<img width="1079" height="828" alt="image" src="https://github.com/user-attachments/assets/5a4368b5-d9e2-4edc-9d24-ed41a5b00ea5" />

# OUTPUT GRAPH :
<img width="880" height="1431" alt="image" src="https://github.com/user-attachments/assets/352077e4-58db-4c34-a678-79acf65bb0f9" />

# RESULT :
The FIR filter was designed using Rectangular window.
