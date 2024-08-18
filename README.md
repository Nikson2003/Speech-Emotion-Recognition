
# Speech Emotion Recognition Website

This project is a real-time Speech Emotion Recognition (SER) web application that predicts emotions from audio using an LSTM (Long Short-Term Memory) model. The application is built using four prominent datasets: CREMA-D, RAVDESS, SAVEE, and TESS.

## Table of Contents
1. [Introduction](#introduction)
2. [Datasets](#datasets)
3. [Model Architecture](#model-architecture)
4. [Website Features](#website-features)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Introduction
The Speech Emotion Recognition (SER) website is designed to identify and analyze human emotions based on speech input in real-time. It uses an LSTM-based deep learning model trained on multiple datasets to achieve high accuracy. The website provides an intuitive interface for users to interact with, allowing them to upload audio files or record their voices directly through the platform.

## Datasets
The model is trained on the following datasets:
- **CREMA-D**: Crowd-sourced Emotional Multimodal Actors Dataset.
- **RAVDESS**: Ryerson Audio-Visual Database of Emotional Speech and Song.
- **SAVEE**: Surrey Audio-Visual Expressed Emotion.
- **TESS**: Toronto Emotional Speech Set.

These datasets encompass a wide range of emotions, including neutral, calm, happy, sad, angry, fearful, surprise, and disgust.

## Model Architecture
The LSTM model was chosen due to its effectiveness in sequence prediction tasks, particularly in processing and analyzing audio signals over time. The model's architecture includes:
- Preprocessing layers to normalize and extract features from audio signals.
- LSTM layers for temporal sequence learning.
- Fully connected dense layers for emotion classification.

## Website Features
- **Real-Time Emotion Prediction**: Users can record or upload their voice, and the website will predict the emotion in real-time.
- **Interactive Dashboard**: A user-friendly interface that displays the detected emotion and confidence scores.
- **Multiple Language Support**: The website can process speech in different languages.
- **Visualization Tools**: Graphical representation of the emotion probabilities and audio waveform.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ser-website.git
   cd ser-website
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download and prepare the datasets**:
   Ensure the datasets (CREMA-D, RAVDESS, SAVEE, TESS) are available in the `data/` directory.

4. **Train the model** (optional):
   If you wish to train the model from scratch:
   ```bash
   python train_model.py
   ```

5. **Run the website**:
   ```bash
   python app.py
   ```

6. **Access the website**:
   Open a browser and go to `http://127.0.0.1:5000/`.

## Usage
- **Record Your Voice**: Click on the 'Record' button to start capturing your voice through the microphone.
- **Upload Audio File**: Use the upload feature to analyze pre-recorded audio files.
- **View Results**: The detected emotion will be displayed with an emoji for better visualization.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or report any issues.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or suggestions, please contact:
- **Nikson Nadar** - [nadarnikson@gmail.com]
- GitHub: [@Nikson2003](https://github.com/Nikson2003)
