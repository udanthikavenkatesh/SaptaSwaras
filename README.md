# 🎵 SaptaSwaras & DeepLearningRagas

A deep learning-based project for extracting musical notes (swaras) and classifying Indian classical ragas using audio input.

---

![image](https://github.com/user-attachments/assets/db770004-bcf8-4585-92e4-ce43d11c9731)


## 📁 Project Overview

### SaptaSwaras

- **Purpose**: Extract the 7 basic swaras (Sa, Ri, Ga, Ma, Pa, Da, Ni) from keyboard-based or instrumental audio input.
- **Requirements**:
  - Clean monophonic audio (no overlapping notes or background noise).
  - Accurate pitch input for best results.

### DeepLearningRagas

- **Purpose**: Classify Indian classical ragas from audio clips using deep learning models.
- **Dataset**: A curated collection of 1280 audio samples across 8 different ragas sourced from YouTube.
- **Models Used**:
  1. **Fully Connected CNN**: For basic spectrogram feature extraction and classification.
  2. **LSTM**: For temporal sequence learning and long-term dependency modeling.
  3. **LSTM + TDNN**: Combines LSTM’s memory with Time-Delay Neural Networks for enhanced temporal feature learning.

---

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/saptaswaras-deeplearningragas.git
   cd saptaswaras-deeplearningragas


