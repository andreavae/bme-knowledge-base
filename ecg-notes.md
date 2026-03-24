# ECG Signal Processing

## What is ECG?
Electrocardiogram (ECG) records the electrical activity of the heart. It is essential for diagnosing cardiac conditions.

## Key Components
- **P wave**: Atrial depolarization
- **QRS complex**: Ventricular depolarization
- **T wave**: Ventricular repolarization

## Clinical Applications
- Arrhythmia detection
- Myocardial infarction diagnosis
- Heart rate variability analysis

## Noise and Artifacts
Real-world ECG signals contain various interferences:
- **Baseline wander**: Low-frequency drift from breathing/movement
- **Power line interference**: 50/60 Hz noise from electrical equipment
- **Muscle artifacts**: High-frequency noise from muscle contractions

## Signal Processing Techniques
- **Digital filtering**: Bandpass filters (0.5-40 Hz) to remove noise
- **Pan-Tompkins algorithm**: R-peak detection for heart rate calculation
- **Wavelet transform**: Feature extraction and denoising
