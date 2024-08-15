# Facial-Emotion-Recognition-using-ML-Python

This project demonstrates how to use Convolutional Neural Networks (CNNs) for emotion detection from facial expressions.

Requirements
Before you begin, make sure you have the following Python packages installed:
pip install numpy

pip install opencv-python

pip install keras

pip3 install --upgrade tensorflow

pip install pillow

Dataset
You need to download the FER2013 dataset to train the model. You can get it from this link on Kaggle-- https://www.kaggle.com/msambare/fer2013

After downloading, place the dataset in a data folder within your project directory.

Training the Emotion Detector
To train the emotion detection model:

Open the trainmodel-checkpoint.ipynb file in a Jupyter environment.
Run the notebook to train the model using the FER2013 dataset.
Note: The training process may take several hours, depending on your hardware. On an i5 processor with 16GB of RAM, it took approximately 4 hours.

After the training is complete, the model structure and weights will be saved as:

emotiondetector.json
emotiondetector.keras

Face Emotion Recognition Using Machine Learning
This project is a practical implementation of facial emotion recognition using machine learning and Python.

You can watch a related tutorial here: https://www.youtube.com/watch?v=aoCIoumbWQY
