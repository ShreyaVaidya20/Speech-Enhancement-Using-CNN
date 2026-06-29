# Speech Enhancement using Convolutional Neural Networks (CNN)

This work presents a deep learning-based speech enhancement system that removes background noise from speech signals using a Convolutional Neural Network (CNN). The workflow combines traditional signal processing with deep learning by converting noisy speech into spectrograms using the Short-Time Fourier Transform (STFT), training a CNN to learn the mapping between noisy and clean speech, and reconstructing enhanced speech with improved clarity. The system effectively suppresses background noise while preserving speech quality, making it suitable for various speech processing applications.

## Features

- Speech denoising using Convolutional Neural Networks (CNN)
- Audio preprocessing with configurable Signal-to-Noise Ratio (SNR)
- STFT-based feature extraction
- CNN model training and testing
- Speech reconstruction using inverse STFT
- Performance evaluation using objective metrics

## Technologies Used

- Python
- PyTorch
- Librosa
- NumPy
- Matplotlib
- SciPy

  ## Dataset

This work utilizes the **TIMIT** dataset as the source of clean speech recordings and the **AURORA** dataset for environmental noise samples. Clean speech signals are mixed with different types of background noise at predefined Signal-to-Noise Ratio (SNR) levels to generate noisy speech for training and evaluation. The dataset includes multiple speakers and diverse noise conditions such as babble, street, train, car, and restaurant noise, allowing the model to generalize effectively across various real-world acoustic scenarios.

