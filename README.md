# Artificial Intelligence Monitoring at the Edge for Smart Nation Deployment

## About the Project 

A NTU EEE FYP project that aims to identify sources of noise pollution in schools using the Google Coral Development Board.

The Google Coral Development Board (Coral Dev Board) uses an attached microphone to listen for noises above a certain intensity threshold. The noises are saved as WAV files before audio features (e.g Log-Mel Spectrogram) are extracted. A Tensorflow Lite model that runs on the Coral Dev Board takes in these audio features as input and outputs the predicted sound classes.

## Sections and Files 

This repository contains files relevant to Part 1 of the project.

**1. Preprocessing**

* Codes to resize audio data, perform noise reduction and data augmentation
* Codes to extract features (Log-Mel Spectrogram) + split data into training and validation data

**2. Model Training**

* Codes to train MobileNetV2 sound classification model
* Trained MobileNetV2 model

**3. Quantization**

* Codes to perform PTQ with int8 tensors and float32 tensors
* Codes to perform QAT with int8 tensors and float32 tensors
* TFLite models compiled for Edge TPU

**4. Noise Monitoring**

* Codes to place noise data in pandas data frame and save as csv file
* Noise data text file downloaded from webserver
* Noise data in CSV file

## Part 2 of the Project

* This portion refers to the creation of a software release that executes the TFLite model compiled for the Edge TPU on the Coral Dev Board.
* Click [here](https://github.com/xychong/noise_analyzer) to go to Part 2 of the project.
