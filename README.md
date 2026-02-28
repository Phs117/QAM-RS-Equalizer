# 16-QAM System BER Simulation

A Python-based simulation of a 16-QAM digital communication system over an AWGN channel to analyze Bit Error Rate (BER) performance.

## Features
* 16-QAM symbol mapping and demapping.
* AWGN channel noise insertion.
* BER calculation and comparison with theoretical values.
* Performance visualization ($E_b/N_0$ vs. BER).

## Requirements
* Python 3
* NumPy
* Matplotlib

## Installation and Usage
1. Clone the repository:
   `git clone https://github.com/Phs117/16-QAM-system-BER.git`
2. Install dependencies:
   `pip install numpy matplotlib`
3. Run the simulation:
   `python main.py`

## Results
The script generates a plot comparing the simulated BER against the theoretical 16-QAM curve, validating the system's performance across different signal-to-noise ratios.
