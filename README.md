# Conference Talk Repository

Welcome to the repository for the code and slides from my conference talk on Convolutional Neural Networks (CNNs) at the 3rd Annual North Carolina Cybersecurity Symposium.

## Overview

This repository contains the Python code discussed during my conference talk, as well as the accompanying slides in PDF format. The code demonstrates the architecture of a CNN model, covering the entire process from loading the data into a pandas DataFrame to saving the trained model, loading it back, and making predictions.

## Contents

1. [Code](#code)
2. [Slides](#slides)

## Code

The Python code provided here illustrates the architecture of the CNN model discussed in the conference talk. The code is organized into the following sections:

- Data Loading: Explains how to load the data into a pandas DataFrame. (you would also need to normalize and preprocess this text. Things like converting to lowercase, etc.)
- Data Tokenization: Tokenizes the data into readable format for the model. 
- Model Definition: Defines the architecture of the CNN model using TensorFlow.
- Model Training: Shows how to train the CNN model using the provided dataset.
- Model Evaluation: Evaluates the performance of the trained model on test data.
- Saving and Loading the Model: Illustrates how to save the trained model to disk and load it back for future use.
- Making Predictions: Demonstrates how to use the trained model to make predictions on new data.

You can find the code in [NCPACE_CNN.py](NCPACE_CNN.py).

## Slides

The slides provided in this repository are in PDF format and correspond to the presentation delivered during the conference talk. They cover key concepts, methodologies, and results discussed during the presentation.

You can find the slides in [ADVANCING DATA LOSS PREVENTION WITH NEURAL NETWORKS DETECTING & PRIORITIZING INCIDENTS.pdf](ADVANCING%20DATA%20LOSS%20PREVENTION%20WITH%20NEURAL%20NETWORKS%20DETECTING%20&%20PRIORITIZING%20INCIDENTS.pdf).

## Getting Started

To get started with the code and slides:

1. Clone this repository to your local machine.
2. Explore the code files to understand the architecture of the CNN model.
3. Review the slides for a comprehensive overview of the topics discussed during the conference talk.
4. Replace the variables with your real data (when loading the dataframe you need to provide your actual data. When preprocessing the data you need to provide the actual feature names and labels you want to use.)

## Requirements

- Python 3
- TensorFlow/Keras
- Pandas
- NumPy
- Scikit-learn
- Joblib
- NumPy
- Pickle



## Acknowledgments

Special thanks to NC PACE for providing the opportunity to present this talk and share the code and slides with the community.
