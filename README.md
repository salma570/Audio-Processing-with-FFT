# 🎵 Audio Processing with FFT — Noise Reduction System

## 📘 Overview
This project implements an **audio processing system** in Python that simulates and enhances audio quality by applying **Fast Fourier Transform (FFT)**-based noise reduction techniques.  
It demonstrates fundamental principles of **digital signal processing (DSP)**, including frequency-domain analysis, filtering, and signal reconstruction.

---

## 🧠 Objectives
- Generate or import an audio signal (e.g., sample of *Moonlight Sonata*).  
- Add artificial noise to simulate real-world signal degradation.  
- Apply FFT analysis to identify and isolate unwanted frequencies.  
- Perform **noise filtering and reduction** using spectral manipulation.  
- Reconstruct the clean signal and visualize transformations.

---
## 🧪 Example Output
- **Input:** Noisy audio sample (e.g., Moonlight Sonata with static)
- **Output:** Enhanced, noise-reduced version with smoothed spectrum  
- **Visualizations:**  
  - Time-domain waveform (before & after filtering)  
  - Frequency spectrum comparison  

<img width="857" height="569" alt="plots_clear" src="https://github.com/user-attachments/assets/16b39a18-0d53-4aca-9b2a-1877fc2fa0bc" />

---

## 🛠️ Tech Stack
**Language:** Python  
**Libraries & Tools:**  
- `NumPy` — numerical and FFT operations  
- `SciPy` — signal processing utilities  
- `Matplotlib` — signal and spectrum visualization  
- `SoundFile` or `wave` — audio input/output  

---

## ⚙️ Features
- 🎚️ **Noise Simulation:** Adds Gaussian or random background noise to clean audio.  
- 🧩 **FFT Analysis:** Converts the signal from time domain to frequency domain for detailed inspection.  
- 🔍 **Peak Detection & Filtering:** Identifies dominant frequency bands and suppresses noisy components.  
- 🔄 **Reconstruction:** Restores the cleaned signal using inverse FFT.  
- 📊 **Visualization:** Plots waveforms and frequency spectra before and after processing.

---

## 🧩 System Workflow
```text
1️⃣ Load or generate original audio signal
2️⃣ Add synthetic noise
3️⃣ Apply FFT → obtain frequency spectrum
4️⃣ Identify and suppress noisy frequencies
5️⃣ Apply inverse FFT to reconstruct audio
6️⃣ Save and visualize processed output
