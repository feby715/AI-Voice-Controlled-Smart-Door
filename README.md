# AI Voice-Controlled Smart Door System Using CNN
# AI Voice-Controlled Smart Door System Using CNN

## Project Overview
This project uses Convolutional Neural Networks (CNNs) and audio features to recognize voice commands and authenticate speakers. It demonstrates door opening and closing through a visual simulation developed in Google Colab.

## Main Features
- Voice command classification: OPEN, CLOSE, and NOISE.
- Speaker authentication: AUTHORIZED and UNAUTHORIZED.
- MFCC-based audio feature extraction.
- CNN-based classification.
- Visual simulation of door opening and closing.

## Technologies Used
- Python
- Google Colab
- TensorFlow/Keras
- NumPy
- Librosa
- Matplotlib

## Datasets
The command-recognition dataset was obtained from Kaggle. A separate set of authorized and unauthorized voice recordings was prepared for speaker authentication.

## Limitations
This project demonstrates door operation through software simulation. It does not physically control a door or lock.

## How to Run
1. Open `AI_project.ipynb` in Google Colab.
2. Install any required libraries.
3. Configure the Kaggle API secret if dataset downloading is required.
4. Run the notebook cells in order.

**Security note:** Never upload API tokens, private voice recordings, or other credentials to the repository.
