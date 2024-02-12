# Malaria Cell Detection

## Overview

This project focuses on the detection of malaria-infected cells using machine learning techniques. It utilizes a dataset of cell images to train and evaluate models for accurate classification of infected and uninfected cells.

## Dataset

The dataset used in this project can be found [here]([link-to-your-dataset](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria)).
Please download the dataset and extract it into the `data/` directory before running the scripts.

## Project Structure

- `data/`: Directory to store the dataset.
- `src/`: Contains the source code for data preprocessing, model training, and evaluation.
  - `preprocess_data.py`: Script for preprocessing the dataset.
  - `train_model.py`: Script for training the machine learning model.
  - `evaluate_model.py`: Script for evaluating the trained model.
- `models/`: Directory to save trained models.
- `results/`: Directory to store evaluation results and visualizations.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/buthinaaa/Malaria-Cell-Detection.git
   cd Malaria-Cell-Detection
