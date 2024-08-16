# Speaker Recognition using Deep Neural Networks

**Introduction**

This repository contains the code and results for my Master's thesis, which focuses on developing a robust speaker recognition system using deep neural networks. The goal of this project was to create a model capable of accurately identifying individuals based on their voice.

![metodologia-diagram](https://github.com/user-attachments/assets/b2c6b5b3-6072-4b29-a148-2508662223e6)


**Methodology**
* **Data Preprocessing:**
  * Conversion of raw audio signals into spectrograms using short-time Fourier transform (STFT).
* **Feature Extraction:**
  * Experimentation with various feature extraction techniques, including:
    * Mel-Frequency Cepstral Coefficients (MFCC)
    * Spectral contrast
    * Mel spectrograms
  * Evaluation of different feature representations based on their ability to capture speaker-specific information.
* **Model Architecture:**
  * Design of a custom convolutional neural network (BetterCNN) tailored for speaker recognition.
  * Comparison with the widely used ResNet50 architecture.
* **Experiments and Results:**
  * Evaluation of the proposed model on multiple datasets (50_speakers, LibriSpeech, TIMIT).
  * Detailed analysis of the performance metrics (accuracy, F1-score).
  * Comparison of BetterCNN with ResNet50 and other baseline models.
  
![image](https://github.com/user-attachments/assets/9a161b66-c64c-4788-a387-8477e2faaade)
![image](https://github.com/user-attachments/assets/cf249a58-0fe6-4ac5-b984-2078d131d1f3)

**Results**

Mel spectrograms were found to be the most effective feature representation for speaker recognition in this study. The proposed BetterCNN model consistently outperformed ResNet50 on all datasets, demonstrating its superior ability to capture the nuances of human speech.

* **Key findings:**
  * BetterCNN achieved an F1-score of 96.11% and accuracy of 96.24% on the 50_speakers dataset.
  * On the LibriSpeech dataset, BetterCNN reached an accuracy of over 99.75%.

**Conclusion**

This research highlights the effectiveness of deep learning techniques for speaker recognition. The proposed BetterCNN model offers a promising approach for developing accurate and efficient speaker identification systems. Future work could explore:

* **Larger datasets:** Training on more diverse and larger datasets.
* **Advanced architectures:** Exploring more complex neural network architectures (e.g., transformers).
* **Multimodal approaches:** Combining audio with other biometric modalities (e.g., facial images).

![image](https://github.com/user-attachments/assets/e122115e-04fc-4472-9e22-f33b448faa6f)
