# 🫀 Heart Sound MFCC Pipeline (with Visualisations)

This repository contains a complete and visually-explained **MFCC feature extraction pipeline** for analyzing heart-sound audio signals.

---

## 📌 What This Project Does

- Loads real `.wav` recordings of heart sounds  
- Applies **preprocessing filters**:
  - High-pass filter (20 Hz) to remove low-frequency drift
  - Low-pass filter (400 Hz) to remove high-frequency noise
  - Savitzky-Golay smoothing for denoising
- Extracts features using the **MFCC pipeline**:
  - Framing + Windowing
  - FFT + Power Spectrum
  - Mel Filter Bank Projection
  - Log Compression
  - DCT to obtain MFCCs
  - Δ and ΔΔ (delta and acceleration) features ( to be added later)
- **Visualises each stage** using Matplotlib

---

## 🎯 Use Case

This pipeline is suitable for:

- **Medical diagnostics research** (e.g., classifying heart murmurs)
- Teaching **digital signal processing** with a hands-on notebook
- Demonstrating **linear algebra in action** with real audio data
- Preprocessing for **CNNs or other deep learning models** working on heart sounds

---

## 📂 Files Included

| File                                  | Description                                        |
|---------------------------------------|----------------------------------------------------|
| `mfcc_pipeline_filter_visual.ipynb`   | The complete, annotated notebook with plots        |
| `README.md`                           | This file explaining the project                   |

---

## 🚀 Getting Started

1. Clone the repo or download the notebook
2. Install dependencies:
   ```bash
   pip install numpy scipy matplotlib librosa

