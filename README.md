# Artificial Intelligence Monitoring at the Edge for Smart Nation Deployment

## About the Project 



## Sections

**1. Preprocessing**

  Contains codes to:
    * Resize audio data, perform noise reduction and data augmentation
    * Extract features (Log-Mel Spectrogram)
    * Split data into training and validation data

**2. Model Training**

Contains:
  * Codes to train MobileNetV2 sound classification model
  * Trained MobileNetV2 model

**3. Quantization**

Contains:
  * Codes to perform PTQ with int8 tensors and float32 tensors
  * Codes to perform QAT with int8 tensors and float32 tensors
  * TFLite models compiled for Edge TPU

**4. Noise Monitoring**

Contains:
  * Code to place noise data in pandas data frame and save as csv file
  * Noise data text file downloaded from webserver
  * Noise data in CSV file
