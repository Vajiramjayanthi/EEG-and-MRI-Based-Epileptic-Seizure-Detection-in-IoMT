# EEG-and-MRI-Based-Epileptic-Seizure-Detection-in-IoMT
Edge Optimized Hybrid Quantum-Classical Ensemble Framework for EEG and MRI Based Epileptic Seizure Detection in IoMT
Accurate and timely detection of epileptic seizures is critical for clinical intervention however, conventional EEG analysis is
constrained by noise, inter-patient variability, and high computational demands. To overcome this the proposed lightweight
Hybrid Quantum classical Ensemble Net (HQCE-Net) optimized for edge device. The proposed pipeline with filtering,
noice reduction scaling to suppress artifacts, followed by extraction of features on EEG sub-band powers (δ, θ, α, β) and
MRI images multi model feature fusion using Quantum Fourier Transform (QFT) and Quantum Wavelet Transform (QWT)
enabling complementary frequency-domain and multi-resolution time–frequency representation while maintaining computational
efficiency. The fused features are standardized using z-score normalization. The complete system is implemented on a
Raspberry Pi 5, On the EEG dataset (CHBMIT), HQCE-Net achieves about 92% accuracy with 92% performance metrics. On
the MRI dataset it achieves 98% accuracy with 98% precision/recall, showing strong and consistent performance across both
EEG and MRI modalities on edge device. Unlike existing EEG seizure detection methods that rely on computationally intensive
deep models or cloud-based processing, This work demonstrates the practical and reliable neurodiagnostic monitoring for
home-based and resource-limited clinical environments.
