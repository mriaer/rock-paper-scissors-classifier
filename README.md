# Image Classifier: Rock, Scissors, Paper

This project is a simple image classification model built using deep learning to classify hand gestures as either "rock", "paper", or "scissors". The model uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## Overview

The goal of this project is to create a deep learning model that can classify images of hand gestures as Rock, Scissors, or Paper. It uses a CNN to process images and make predictions.

## Requirements

To run this project, you need to have the following Python libraries installed:

- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`
- `opencv-python`
- `pandas`

You can install them using pip:

```bash
pip install tensorflow keras numpy matplotlib opencv-python pandas
```

## Dataset

The dataset for the project is composed of images of hand gestures. Each folder in the dataset/ directory represents a class (rock, paper, or scissors). You can either use your own dataset or download a publicly available one for gesture recognition, such as from Kaggle. You can download the dataset from [this link](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).


## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/mriaer/rock-paper-scissors-classifier
```
```bash
cd rock-paper-scissors-classifier
```

### 2. Install Dependencies
```bash
pip install tensorflow keras numpy matplotlib opencv-python pandas
```

### 3. Open Jupyter Notebook
```bash
jupyter notebook Proyek_Akhir_Klasifikasi_Gambar.ipynb
```

### 4. Run the Code

## Model Architecture

The model uses a Convolutional Neural Network (CNN) to classify the images. It consists of:
- Several convolutional layers for feature extraction
- MaxPooling layers to reduce dimensionality
- Fully connected layers for classification
- Softmax activation in the output layer for multi-class classification

## Results

After training, the model should be able to predict hand gestures as one of the three classes: rock, paper, or scissors. You can test the model using your own images or the provided dataset.
