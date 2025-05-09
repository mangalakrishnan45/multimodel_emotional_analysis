# multimodel_emotional_analysis
# Multimodal Emotional Analysis

## Project Overview

This project focuses on analyzing emotional expressions using multimodal data, primarily audio. The dataset used is the **Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)**, which contains recordings of speech and song expressing various emotions.

## Dataset

The RAVDESS dataset is downloaded directly from [Zenodo](https://zenodo.org/record/1188976) and extracted for further processing. The dataset contains audio recordings that are categorized by different emotional states.

## Main Features

* **Data Acquisition:** Downloads and unzips the RAVDESS dataset.
* **Data Exploration:** Plays sample audio files using the IPython display module.
* **Feature Extraction:** Uses the `librosa` library to extract relevant features such as MFCCs from audio files.
* **Data Preprocessing:** Encodes labels and normalizes features for model training.
* **Model Building:** Implements a neural network using Conv1D, LSTM, and Dense layers with TensorFlow/Keras.

## Dependencies

* Python 3.x
* IPython
* Pandas
* Librosa
* TensorFlow
* Scikit-learn

## Usage

To run the notebook, execute the cells sequentially. Ensure that all dependencies are installed beforehand.
