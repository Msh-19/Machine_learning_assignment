# Animal Classifier Project

## Overview

Welcome to the Animal Classifier project! This project leverages machine learning to classify animals based on their appearance. The classifier takes an image of an animal as input and predicts the species of the animal.

## Authors

- Metsehafe Eyasu (ID: 0852/13)
- Michael Engida (ID: 0859/13)
- Mohammed Mehad (ID: 0907/13)
- Mohammed Restem (ID: 0911/13)
- Mohammed Shemim (ID: 0912/13)

## Features

- **Image Preprocessing:** Resizes and normalizes input images.
- **Model Training:** Uses a convolutional neural network (CNN) to learn from a dataset of labeled animal images.
- **Prediction:** Classifies new images and outputs the predicted animal species.
- **Evaluation:** Assesses the model's performance using metrics like accuracy, precision, and recall.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/animal-classifier.git
   cd animal-classifier
  ``
   Set up a virtual environment and activate it:


python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

```bash
pip install -r requirements.txt
```
Usage
Prepare the dataset:

Ensure your dataset is organized in a directory structure where each subdirectory is named after the animal species it contains images of.
Train the model:

```bash
python train.py --dataset /path/to/dataset --epochs 50 --batch-size 32
```
Make predictions:

```bash

python predict.py --image /path/to/image.jpg
```
Evaluate the model:

```bash
python evaluate.py --dataset /path/to/dataset
```
