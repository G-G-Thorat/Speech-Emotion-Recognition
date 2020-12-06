# Speech-Emotion-Recognition
Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech.
This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

Prequisites:

To run code in the JupyterLab, you’ll first need to run it with the command prompt:
C:\Users\GT>jupyter lab

To build a model to recognize emotion from speech using the librosa and sklearn libraries and the RAVDESS dataset.

You’ll need to install the following libraries with pip:
pip install librosa soundfile numpy sklearn pyaudio

STEPS:
1. Make necessary imports: import librosa
                           import soundfile
                           import os, glob, pickle
                           import numpy as np
                           from sklearn.model_selection import train_test_split
                           from sklearn.neural_network import MLPClassifier
                           from sklearn.metrics import accuracy_score
2. Define a function extract_feature to extract the mfcc, chroma, and mel features from a sound file
3. Now, let’s define a dictionary to hold numbers and the emotions
4. Now, let’s load the data with a function load_data()
5. Time to split the dataset into training and testing sets!
6. Observe the shape of the training and testing datasets
7. And get the number of features extracted.
8. Now, let’s initialize an MLPClassifier.
9. Fit/train the model.
10. Let’s predict the values for the test set.
11. To calculate the accuracy of our model, we’ll call up the accuracy_score() function we imported from sklearn.   
