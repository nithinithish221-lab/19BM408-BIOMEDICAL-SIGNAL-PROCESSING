# HANNING WINDOW BASED FIR FILTER DESIGN

# AIM:

To design a Low Pass FIR filter using Hanning (Hann) Window and analyze its response.
# THEORY :

Hanning window is defined as:

w(n)=0.5-0.5cos⁡(2πn/N)

Characteristics:

1)Smooth tapering at ends

2)Reduced spectral leakage

3)Moderate stopband attenuation (~31 dB)

4)Wider main lobe than Hamming

Design Equation:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Select N and ωc
2.	Compute ideal response
3.	Generate Hanning window
4.	Multiply and obtain FIR coefficients
5.	Plot response

# MATLAB CODE :
<img width="1080" height="953" alt="image" src="https://github.com/user-attachments/assets/f26a3a8c-936e-49a6-8c9d-20df337de99b" />

# OUTPUT GRAPH :
<img width="975" height="1466" alt="image" src="https://github.com/user-attachments/assets/4f7aaa5c-b7cc-4e6c-b957-7df7f5f60676" />

# RESULT :
The FIR filter was designed using Hanning window.
