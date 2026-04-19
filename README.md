# 1 kHz Multiple Feedback Band-Pass Filter using LM324

## Description
Design and implementation of a 1 kHz Multiple Feedback (MFB) band-pass filter using LM324. The circuit filters desired frequencies, converts output to DC via rectifier, and uses a comparator-driven LED for indication. Simulated and tested with results matching theory.

---

## Objective
- Design a band-pass filter centered at 1 kHz  
- Allow only a specific frequency range to pass  
- Indicate valid signal detection using LED  

---

## Components Used
- LM324 Op-Amp  
- Resistors  
- Capacitors  
- Diodes (Bridge Rectifier)  
- LED  
- Power Supply  

---

## Working Principle
The circuit uses an MFB topology to achieve frequency selectivity around 1 kHz.  
The filtered AC signal is rectified and smoothed to DC.  
A comparator compares this voltage with a reference level, turning the LED ON when the desired frequency is detected.

---

## Results
- Center Frequency ≈ 1 kHz  
- Bandwidth ≈ 200 Hz  
- Output closely matches theoretical design  

---

## Applications
- Audio signal processing  
- Noise filtering  
- Communication systems  

---

## Author
**Abhinav Racha Battuni**  
RV College of Engineering (RVCE)

---

## Links
- GitHub: https://github.com/abhinavrach  
- Repository: https://github.com/abhinavrach/bandpass-filter
