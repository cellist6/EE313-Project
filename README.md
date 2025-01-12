# EE313-Project: Analog Communication System Design

## Overview  
This project implements a digital communication system for Amplitude Modulation (AM) and Frequency Modulation (FM) in **Simulink**. It demonstrates the processes of modulating audio signals, transmitting them through an Additive White Gaussian Noise (AWGN) channel, and recovering the original signals through demodulation. The system simulates realistic communication scenarios, ensuring accurate recovery of transmitted audio despite noise interference.  

## Features  
- **AM Modulation & Demodulation:**  
  - Modulates two audio signals onto distinct carrier frequencies.  
  - Adds AWGN noise to simulate real-world conditions.  
  - Demodulates signals using envelope detectors and bandpass filters for signal separation and recovery.  

- **FM Modulation & Demodulation:**  
  - Modulates audio signals by encoding information in frequency variations.  
  - Uses discrete integrators, gain blocks, and cosine blocks for FM signal generation.  
  - Demodulates signals through filtering, differentiation, and envelope detection.  

## Architecture  
### AM Modulation  
1. Input audio signals are modulated using carrier frequencies.  
2. Signals are combined and passed through an AWGN channel.  
3. Demodulation involves bandpass filtering and envelope detection to recover the original signals.  

### FM Modulation  
1. Input audio signals are scaled, integrated, and modulated with carrier frequencies.  
2. The combined FM signal is transmitted through an AWGN channel.  
3. Demodulation involves discrete filtering, differentiation, and envelope detection to retrieve the original messages.  

### Block Diagram  
Refer to the report for detailed block diagrams of AM and FM modulation and demodulation.  

## Files in the Repository  
- **am.slx:** Simulink file for AM modulation and demodulation.  
- **fm.slx:** Simulink file for FM modulation and demodulation.  
- **Analog Communication System Design_ Project Report.pdf:** Detailed project report explaining the system design and implementation.  
- **Audio_Files/**: Folder containing input and output audio files for testing.  

## License  
This project is licensed under the [MIT License](LICENSE).  
