# Speech Enhancement using Convolutional Neural Networks (CNN)

This project presents a deep learning-based speech enhancement system that removes background noise from speech signals using a Convolutional Neural Network (CNN). The workflow combines traditional signal processing with deep learning by converting noisy speech into spectrograms using the Short-Time Fourier Transform (STFT), training a CNN to learn the mapping between noisy and clean speech, and reconstructing enhanced speech with improved clarity. The system effectively suppresses background noise while preserving speech quality, making it suitable for various speech processing applications.

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


## Publication

**Audio Denoising: Speech Enhancement using Convolutional Neural Networks**

Published in the **5th International Conference on Recent Trends in Machine Learning, IoT, Smart Cities and Applications (ICMISC 2024).**
https://doi.org/10.1007/978-981-97-8865-1_14
