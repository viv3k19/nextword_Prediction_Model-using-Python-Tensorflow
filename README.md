# Next Word Prediction
The Next Word Prediction repository contains code for training a next word prediction model using LSTM (Long Short-Term Memory) and TensorFlow. The model is designed to predict the next word in a sequence of words based on the input data.

Next word prediction is a task in natural language processing that aims to predict the most likely word that follows a given sequence of words. It has applications in various fields such as text generation, autocomplete, and language translation. This repository provides a practical implementation of a next word prediction model using deep learning techniques.

## How it Works
The model is trained on a dataset containing text data, in this case, the medium_data.csv file. The code reads the dataset using pandas and preprocesses the text by tokenizing and creating input sequences. It then constructs a neural network model using TensorFlow and trains it on the input sequences.

The neural network architecture consists of an embedding layer, bidirectional LSTM layers, and a dense layer with a softmax activation function. The model is trained using the Adam optimizer and categorical cross-entropy loss. After training, the model can be used to predict the next word in a given input sequence.

## Prerequisites
Before using the code, ensure that you have the following prerequisites installed:
`Python 3`
`TensorFlow`
`pandas`
`numpy`

## Installation

Clone the repository:
```shell
git clone https://github.com/viv3k19/nextword_Prediction_Model-using-Python-Tensorflow.git
```

## Usage
* To use the next word prediction model, follow these steps:
* Download the dataset medium_data.csv and place it in the project directory.
* Open the Jupyter Notebook nextword_Prediction.ipynb.
* Run the notebook cell by cell to execute the code.

## Results

* Accuracy & Test Results

![epochResults](https://github.com/viv3k19/nextword_Prediction_Model-using-Python-Tensorflow/assets/82309435/6ef9d422-fc41-455d-b7c9-271f69d398d1)

* Examples

![inputExamples](https://github.com/viv3k19/nextword_Prediction_Model-using-Python-Tensorflow/assets/82309435/1236e4ab-d2d5-4f97-8e5f-7129f7f9be42)

* Output

![outputPredictedWords](https://github.com/viv3k19/nextword_Prediction_Model-using-Python-Tensorflow/assets/82309435/58699d07-81fe-44d2-99ff-f5ac112e06b6)

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
