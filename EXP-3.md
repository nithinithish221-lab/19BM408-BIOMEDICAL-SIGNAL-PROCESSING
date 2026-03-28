# DIT–FAST FOURIER TRANSFORM (FFT) USING RADIX-2 ALGORITHM
# AIM:
To compute the Fast Fourier Transform (FFT) of a discrete-time signal using the Radix-2 Decimation-in-Time (DIT) algorithm using MATLAB.

# APPARATUS REQUIRED :
•	Computer / Laptop

•	MATLAB software

# Theory :
The Fast Fourier Transform (FFT) is a fast method of computing the Discrete Fourier Transform (DFT).
In the Radix-2 Decimation-in-Time (DIT) FFT:
	The input signal is divided first (decimated in time)
	The signal is split into even and odd indexed samples
	Smaller DFTs are computed
	Results are combined using butterfly operations
The Radix-2 DIT FFT requires the number of samples to be a power of 2:

N=2^m

This method reduces the computational complexity from:

DFT: N^2

FFT: N〖log⁡〗_2 N

Key Features of DIT-FFT :  
1) Decimation is done in time domain .

2) Input sequence is bit-reversed .
  
3) Output is in natural order  .
  
4) FFT is computed in log₂N stages.

# Algorithm :
1)Start the program

2)Define a discrete-time signal of length N=2^m

3)Rearrange the input in bit-reversed order

4)Apply FFT using Radix-2 DIT method

5)Compute the magnitude spectrum

6)Plot the FFT output

7)Stop the program

# MATLAB CODE:
<img width="976" height="1600" alt="image" src="https://github.com/user-attachments/assets/15fc76ac-b251-460a-aee5-293a15b8d63f" />

# OUTPUT GRAPH :
<img width="881" height="1438" alt="image" src="https://github.com/user-attachments/assets/694606be-d8eb-4163-8fd4-5a8ee1d74640" />

# RESULT:
Thus, the Fast Fourier Transform of the given discrete-time signal was successfully computed using the Radix-2 Decimation-in-Time (DIT) FFT algorithm in MATLAB.


