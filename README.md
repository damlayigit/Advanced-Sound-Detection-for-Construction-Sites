# Advanced-Sound-Detection-for-Construction-Sites
Sound detection prototype for construction automation, featuring machine and material detection using audio signal processing and machine learning. Implements feature extraction, classification algorithms, and computer vision techniques to analyze and monitor machinery operations.
Sound Recognition Prototype for Industrial Automation
Overview
This project is a sound recognition prototype aimed at improving construction automation by detecting and identifying different machines and the materials they work with. The system uses audio signal processing, feature extraction, and machine learning algorithms to monitor machine operations in manufacturing environments. It is capable of distinguishing between various types of machinery and their materials, as well as determining the number of times a machine has been operated.

Features
Machine and Material Detection: Identifies different types of machines and the materials they are working on (e.g., drill on concrete, grinder on brick).
Accuracy and Performance: Achieved up to 80% accuracy with the RandomForest classifier. Performance varies depending on background noise and the length of audio samples.
Repetition Counting: Accurately determines the number of times a machine is used by analyzing sound wave patterns.
Feature Extraction: Extracts MFCC, Chroma, Contrast, and Tonnetz features from audio files for classification.
Classifier Comparison: Includes results from various classifiers like RandomForest, AdaBoost, KNN, and MLP.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/damlayigit/Advanced-Sound-Detection-for-Construction-Sites.git 
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Prepare your dataset:

Place your recorded audio files in the ./data/ directory. The system is designed to work with .wav files. Ensure that each audio file is clearly named according to the machine and material being recorded.
Run the feature extraction and classification:

bash
Copy code
python main.py
View the results:

The classification results and analysis will be output to the console and saved in the specified directory.
Usage
Adding New Audio Data: To train the model on new data, simply add your .wav files to the ./data/ directory and rerun the script.
Classifier Tuning: You can adjust the machine learning model parameters in the main.py script to optimize performance.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
