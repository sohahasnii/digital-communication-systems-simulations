# Digital Communication Systems Simulation

A MATLAB-based project to understand and simulate digital communication techniques, study the effect of noise on transmitted signals, and compare system performance using Bit Error Rate (BER).

## Objectives

- Understand the fundamentals of digital communication systems.
- Simulate digital modulation techniques such as ASK, FSK, and BPSK.
- Study the effect of Additive White Gaussian Noise (AWGN) on transmitted signals.
- Demodulate received signals and recover the original data.
- Calculate and compare Bit Error Rate (BER) at different Signal-to-Noise Ratios (SNRs).

## Tools and Technologies

- **MATLAB** — signal generation, modulation, demodulation, and analysis
- **Digital Communication Theory** — modulation, noise, SNR, and BER

## Topics Covered

| Topic | Description |
|---|---|
| Binary Data Generation | Generation of random binary sequences |
| ASK Modulation | Represents binary data using different carrier amplitudes |
| FSK Modulation | Represents binary data using different carrier frequencies |
| BPSK Modulation | Represents binary data using two carrier phases |
| AWGN Channel | Models noise introduced during signal transmission |
| Demodulation | Recovers binary data from the received signal |
| BER Analysis | Measures the number of incorrectly received bits |

## System Workflow

1. Generate a random binary data sequence.
2. Modulate the binary data using a selected modulation technique.
3. Transmit the modulated signal through an AWGN channel.
4. Demodulate the received noisy signal.
5. Compare the transmitted and received bits.
6. Calculate BER and observe how it changes with SNR.

## Expected Results

- Visualize the original binary sequence and modulated waveforms.
- Observe the effect of noise on the received signal.
- Compare transmitted and demodulated bit sequences.
- Plot BER against SNR for different modulation schemes.
- Understand how modulation choice affects communication reliability.

## How to Run

1. Clone or download this repository.
2. Open MATLAB.
3. Navigate to the folder containing the required `.m` file.
4. Run the script.
5. Observe the generated waveforms, simulation results, and performance plots.

## Future Improvements

- Compare ASK, FSK, and BPSK under identical channel conditions.
- Add QPSK modulation and demodulation.
- Investigate the effects of different noise levels.
- Compare simulated BER curves with theoretical results.
- Explore more advanced techniques such as OFDM.


