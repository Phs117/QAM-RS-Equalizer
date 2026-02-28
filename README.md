# 16-QAM System with ZF Equalization and Reed-Solomon Coding

A comprehensive Python simulation of a digital communication system. This project analyzes Bit Error Rate (BER) performance over a distorted channel using equalization and forward error correction (FEC).

## Features
* **Modulation:** 16-QAM mapping and demodulation.
* **Pulse Shaping:** Square Root Raised Cosine (SRRC) filtering for transmission and reception.
* **Channel:** Distorted channel simulation with AWGN (Additive White Gaussian Noise).
* **Equalization:** Zero-Forcing (ZF) FIR Equalizer with delay optimization to mitigate Inter-Symbol Interference (ISI).
* **Error Correction:** Reed-Solomon (RS) coding using the `galois` library for robust data recovery.
* **Visualization:** Plots for Channel Frequency Response (CFR), Constellations, and BER vs. $E_b/N_0$ curves.

## Requirements
* Python 3
* NumPy / SciPy
* Matplotlib
* Pillow (PIL)
* tqdm
* galois

## Installation and Usage
1. Clone the repository:
   `git clone https://github.com/Phs117/16-QAM-system-BER.git`
2. Install dependencies:
   `pip install numpy scipy matplotlib pillow tqdm galois`
3. Ensure an image named `image.tif` is in the directory (for image transmission functions).
4. Run the simulation:
   `python main.py`

## Results
The script calculates the simulated BER by comparing transmitted and received bit blocks, accounting for the gains provided by the Reed-Solomon decoder and the effectiveness of the Zero-Forcing equalizer against channel distortion.

 <img width="2095" height="1609" alt="ber" src="https://github.com/user-attachments/assets/f130045b-b778-466e-b806-ad825a2b6289" />


