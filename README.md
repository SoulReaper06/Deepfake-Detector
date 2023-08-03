# Deepfake-Detector 

The dataset was downloaded from kaggle deepfake detection challenge: https://www.kaggle.com/c/deepfake-detection-challenge/data ( the compressed data of 4 GB)

Detailed Description of each file :

1. capture_img - This file converts the video to face image i.e it uses dlib library of Python ( made up of HOG and CNN face detectors ) to detect face in the video and convert into an image
2. deepfake_detection_train - This file is used to train the dataset and create a model for detection . This dataset has been taken from kaggle ( this is a miniature form of original data , actual dataset is bulky ( more than 400gb) but can improve the model and provide better results.
3. model_play -  this file loads the created model and take input as a video file and return if its a fake or not 
