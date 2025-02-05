# Facial-Emotion-Recognition-using-ML-Python
# Codes zip-file download - https://drive.google.com/file/d/1aoa2G3JyCk5-Gty7e8S1gxS4kRpMToP1/view?usp=drive_link
![all expressions img](https://github.com/user-attachments/assets/62b83ed2-f293-43ab-99eb-14fbf1b175cb)

This project demonstrates how to use Convolutional Neural Networks (CNNs) for emotion detection from facial expressions.

Requirements
Before you begin, make sure you have the following Python packages installed:
### Packages need to be installed
pip install numpy

pip install opencv-python

pip install keras

pip3 install --upgrade tensorflow

pip install pillow

### Download FER2013 dataset
You need to download the FER2013 dataset to train the model. You can get it from this link on Kaggle-- https://www.kaggle.com/msambare/fer2013

After downloading, place the dataset in a data folder within your project directory.

### Train Emotion detector
To train the emotion detection model:

Open the trainmodel-checkpoint.ipynb file in a Jupyter environment.
Run the notebook to train the model using the FER2013 dataset.
Note: The training process may take several hours, depending on your hardware. On an i5 processor with 16GB of RAM, it took approximately 4 hours.

After the training is complete, the model structure and weights will be saved as:

emotiondetector.json
emotiondetector.keras

### Testing
### Run your emotion detection test file
python trialvideotester.py

# Face Emotion Recognition Using Machine Learning
This project is a practical implementation of facial emotion recognition using machine learning and Python.

# You can watch a related tutorial here: https://www.youtube.com/watch?v=aoCIoumbWQY


###Results:
![all expressions of me img](https://github.com/user-attachments/assets/e2fe932d-ea59-4ce6-8bbe-652623d9b7fd)


