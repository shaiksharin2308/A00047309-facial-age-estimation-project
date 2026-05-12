# Facial Age Estimation Using Deep Learning

## Project Overview

This project investigates facial age estimation using deep learning in Google Colab. The work is organised around data preparation, custom CNN experimentation, autoencoder-based representation learning, transfer learning, and a final demo notebook.

The project includes both regression models, which predict a specific age value, and classification models, which predict broader age categories.

The main focus is not only model accuracy, but also understanding how different design choices affect training behaviour, validation performance, overfitting, and runtime.

## Dataset

Dataset used:

frabbisw/facial-age

The dataset is downloaded through the Kaggle API inside the notebooks. The notebooks create CSV manifest files for reproducible loading and splitting.

## Notebook Structure

1. 01_data_preparation_colab.ipynb
- Downloads dataset
- Creates train/validation/test splits
- Performs preprocessing and exploratory analysis

2. 02_part2_custom_cnn_training_colab.ipynb
- Custom CNN regression and classification experiments
- Activation comparisons
- Kernel size comparisons
- Pooling and skip connection experiments
- Dense layer variations
- Augmentation and regularisation experiments

3. 03_part3_autoencoder_transfer_backbone_colab.ipynb
- Autoencoder training
- Transfer learning
- Pretrained backbone models
- Representation learning experiments

4. 04_demo_load_models_and_test_colab.ipynb
- Loads saved models
- Runs predictions on held-out test data
- Visualises final outputs

## Running the Project

Recommended order:

1. 01_data_preparation_colab.ipynb
2. 02_part2_custom_cnn_training_colab.ipynb
3. 03_part3_autoencoder_transfer_backbone_colab.ipynb
4. 04_demo_load_models_and_test_colab.ipynb



## Requirements

Main libraries used:
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- OpenCV
- Pillow
- Kaggle API

All required packages are listed in requirements.txt.

## Notes

The repository excludes datasets, checkpoints, generated CSV files, Kaggle credentials and virtual environment folders to keep the repository lightweight.

The final report and presentation are submitted separately through Brightspace.
