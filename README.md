# ecg-signal-denoising-benchmark
Benchmarking Spectral and Wavelet Filtering for Peak Detection in Wearable ECG Signals (MIT-BIH Database)
# Benchmarking Spectral & Wavelet Filtering for Wearable ECG Signals

An end-to-end computational research framework evaluating Butterworth Band-Pass filtering and Discrete Wavelet Transforms (DWT) for restoring clinical accuracy in noisy ECG signals from the PhysioNet MIT-BIH Arrhythmia Database.

## Key Results
Evaluated across 5 diverse patient records using a Pan-Tompkins peak detection pipeline:
- **Mean Error on Unfiltered Signals:** 32.32 BPM
- **Mean Error on Filtered Signals:** 0.26 BPM
- **Clinical Error Reduction:** 99.19%

## Repository Structure
- `ecg_denoising_benchmark.ipynb`: Complete Python code for data ingestion, noise modeling, filtering, and Pan-Tompkins evaluation.
- `ECG_Filtering_IEEE_Paper.pdf`: IEEE-formatted two-column manuscript draft.

## Author
- **Your Name** — B.Tech ECE, Netaji Subhas University of Technology (NSUT), New Delhi
