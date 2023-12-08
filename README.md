# Hand Sign Language Recognition with OpenCV and Keras

## Overview

This project focuses on creating a Hand Sign Language Recognition model using OpenCV and Keras. The system consists of two main components - `dataCollection.py` for gathering training data and `test.py` for testing the sign language model in real-time. The integration of OpenCV for image processing and Keras for deep learning facilitates real-time recognition of hand signs.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Data Collection](#data-collection)
- [Model Testing](#model-testing)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sign language is an essential means of communication for individuals with hearing impairments. This project aims to bridge the communication gap by recognizing hand signs and translating them into corresponding symbols. The combination of OpenCV and Keras allows for efficient image processing and deep learning-based classification.

## Features

The key features of the Hand Sign Language Recognition model include:

- **Data Collection (`dataCollection.py`):** Collects images for training the model.
- **Model Testing (`test.py`):** Real-time testing of the trained model using live video feed.
- Classification of hand signs into predefined symbols.
- Easy integration with existing applications or devices for enhanced accessibility.

## Installation

To run the Hand Sign Language Recognition model locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/hand-sign-language.git
   ``` 

## Data Collection

Run the data collection script to gather training data:

```bash
python dataCollection.py
```

Follow the on-screen instructions to capture images for different hand signs.

## Model Testing

Run the model testing script for real-time recognition:

```bash
python test.py
```

Activate the webcam and test the sign language recognition model in real-time.

## Results

The performance and accuracy metrics of the model are detailed in the `results.md` file. This document includes insights into the model's strengths, limitations, and potential improvements.
