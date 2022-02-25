# Artificial Intelligence Monitoring at the Edge for Smart Nation Deployment

## About the Project 



## Sections and Files 

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
