# 💗 ECG Signal Processing and Arrhythmia Detection using MATLAB

This project implements a complete pipeline for **ECG signal analysis** and **arrhythmia detection** using MATLAB. It simulates the kind of real-time signal processing used in wearable heart monitoring devices, with a focus on biomedical signal filtering, R-peak detection, and heart rate calculation.

---

## 🎯 Objective

To analyze ECG signals using MATLAB and detect abnormal patterns (arrhythmias) based on heart rate variability and waveform shape.

---

## 🛠️ Tools & Technologies

- MATLAB (R2020 or later)
- Signal Processing Toolbox
- Biomedical Signal Datasets (e.g., MIT-BIH or sample ECG data)
- Filters (Bandpass, Notch)
- Peak detection algorithms

---

## ⚙️ Workflow

1. **Load ECG Signal** (from .mat or .csv files)
2. **Preprocessing**  
   - Noise filtering (baseline drift & powerline interference)  
   - Normalization and smoothing  
3. **Feature Extraction**  
   - R-peak detection  
   - RR-interval and heart rate calculation  
4. **Arrhythmia Detection Logic**  
   - Identify bradycardia (<60 bpm), tachycardia (>100 bpm), irregular RR intervals  
5. **Visualization**  
   - Annotated ECG waveform with R-peaks and heart rate
   - Time-domain plots and alert messages for arrhythmia

