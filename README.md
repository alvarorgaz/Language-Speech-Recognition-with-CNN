# Language-Speech-Recognition-with-CNN

**Author:**

I am Álvaro Orgaz Expósito, a data science student at Aalto (Helsinki, Finland) and a statistician from UPC-UB (Barcelona, Spain).

**Abstract:**

This repository contains the final project of the Speech Recognition course in my master's degree in Data Science at Aalto (Helsinki, Finland). The main goal is to classify speech audio files into 6 languages: Estonian, German, Mandarin, English, Spanish, Farsi, and Kabyle. The model used is a CNN neural network using Log-Mel-Spectrogram and MFCC as input features. The data used is a subset of approximately 50 hours of audio files from the Mozilla Common Voice speech dataset, freely available at https://voice.mozilla.org. I have selected a random subsample of audio files and converted them from MP3 format to waveform WAV files at a frequency of 16 kHz with a normalized volume of -3 dBFS. More details in file *report/report.pdf*.

In the *data* folder you can find:
  - The labels of train and test files in *train_labels.txt* and *test_labels.txt*
  - *train* and *test* folder with an 6 WAV files each one (1 example for each language)
  - *features_extraction* folder with extracted features for the example WAV files (following the structure of folders needed in the code)

**Code:**

The project has been developed in Python using main modules *Keras* and *librosa* with Jupyter Notebook.
