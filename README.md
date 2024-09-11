# Advanced-Sound-Detection-for-Construction-Sites
Sound detection prototype for construction automation, featuring machine and material detection using audio signal processing and machine learning. Implements feature extraction, classification algorithms, and computer vision techniques to analyze and monitor machinery operations.
Sound Recognition Prototype for Industrial Automation
Overview
This project is a sound recognition prototype aimed at improving construction automation by detecting and identifying different machines and the materials they work with. The system uses audio signal processing, feature extraction, and machine learning algorithms to monitor machine operations in manufacturing environments. It is capable of distinguishing between various types of machinery and their materials, as well as determining the number of times a machine has been operated.

# Features

Identifies different types of machines and the materials they are working on (e.g., drill on concrete, grinder on brick).
Achieved up to 86% accuracy with the Support Vector classifier. Performance varies depending on background noise and the length of audio samples.
Accurately determines the number of times a machine is used by analyzing sound wave patterns.
Extracts MFCC, Chroma, Contrast, and Tonnetz features from audio files for classification.
Includes results from various classifiers like Support Vector, RandomForest, AdaBoost, KNN, and MLP.

# Installation

Clone the repository:

git clone https://github.com/damlayigit/Advanced-Sound-Detection-for-Construction-Sites.git

Install the required libraries.

Train the Model: Run the training script to train the classifier on the dataset: python train_model.py

Use the Model: To recognize a sound, place your audio files in the desired folder and run: python use_model.py

Add New Recordings: Add new .wav recordings to the New_Recordings/ folder and update the filepath in the script:

filepath = r"./New_Recordings/NewRecording1.wav"

Make sure your recordings are in .wav format before using them with the model.

View the results:

The classification results and analysis will be output to the console and saved in the specified directory.

# Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
