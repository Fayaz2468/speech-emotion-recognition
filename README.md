
# Emotion Recognition from Speech

## Overview

This project focuses on recognizing emotions from speech audio using machine learning techniques. The goal is to analyze vocal features to identify various emotional states such as happiness, sadness, anger, and surprise.


## Features

- Speech emotion recognition with multiple emotions.
- User-friendly interface for testing audio files.
- Visualizations of feature extraction and model performance.

## Installation

1. Clone the repository:

2. Navigate to the project directory:
   ```bash
   cd speech-emotion-recognition
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

This project utilizes the TESS dataset, which contains audio recordings labeled with various emotions. 

## Model Architecture

The model is based on LSTM. It processes audio features extracted using mfcc.

## Results

The model achieves an accuracy of 98.66 on the validation set. Visualizations of the results can be found in the `/results` directory.
