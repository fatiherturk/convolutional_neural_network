# Convolutional Neural Network (CNN) for Image Classification

This project involves building, training, and classifying a single test image a Convolutional Neural Network (CNN) using TensorFlow and Keras. CNN is trained to classify cats and dogs.

## Requirements

To run this project you need the following requirements:
- TensorFlow (Version the code runs on: 2.11.0)
- Keras
- NumPy

You can use the following commands to install these requirements:

pip install tensorflow
pip install keras
pip install numpy


## Data Preparation

The project uses training and testing datasets in a folder called "dataset". The training dataset should be located in a subfolder named "training_set" and the testing dataset should be located in a subfolder named "test_set". Each subfolder must contain subfolders representing classes.

## Running the Code

To run the main code of the project, you can follow the steps below:

1. Build and train the CNN model by running the `main.py` file.
2. To classify a test image, go to the `single_prediction` folder.
3. Add a test image such as `cat_or_dog_3.jpg` to this folder.
4. Re-run `main.py` to make a single guess.
