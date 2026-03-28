# COMPUTATION OF DISCRETE FOURIER TRANSFORM (DFT) OF A DISCRETE-TIME SIGNAL
#  Aim :
To compute and plot the Discrete Fourier Transform (DFT) of a given discrete-time signal using MATLAB.
# Apparatus / Software Required:
•	Computer / Laptop

•	MATLAB software
# Theory :
A discrete-time signal may contain multiple frequency components.
The Discrete Fourier Transform (DFT) converts a signal from the time domain into the frequency domain and shows the strength of each frequency present in the signal.
MATLAB computes DFT efficiently using the Fast Fourier Transform (FFT) algorithm.

Mathematical Expression:
X(k)=∑_(n=0)^(N-1)▒〖x(n)" " 〗 e^(-j2πkn/N)

Where:
	x(n)→ input signal.
  X(k)→ frequency spectrum.
  N→ number of samples.

# Algorithm :
	1) Start the program
	2) Define the discrete-time signal x(n)
	3) Find the length of the signal
	4) Compute the DFT using fft()
	5) Calculate magnitude spectrum using abs()
	6) Plot the DFT using stem()
	7)Stop the program

# MATLAB CODE :
<img width="906" height="1600" alt="image" src="https://github.com/user-attachments/assets/dfe24ffc-b3d8-4fca-9aaf-bed3ec1838aa" />

# OUTPUT GRAPH :
<img width="906" height="1600" alt="image" src="https://github.com/user-attachments/assets/4b9d59d5-9351-4c17-9c02-8605be0ee673" />

# Result :
Thus, the Discrete Fourier Transform of the given discrete-time signal was successfully computed and plotted using MATLAB.



