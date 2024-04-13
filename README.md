# Deep Learning Image Classification with Transfer Learning and GradCAM

## Overview
This project demonstrates image classification using deep learning techniques, specifically transfer learning with the ResNet50 model, and monitoring model progress using GradCAM visualization. The goal is to classify images into two classes using a binary classification approach.

## Dependencies
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook (for interactive visualization)

## Usage

### 1.Training the Model:

- Run the Jupyter Notebook or Python script for model training (train_model.ipynb or train_model.py).
- Adjust hyperparameters, data augmentation techniques, and model architecture as needed.

### Monitoring Model Progress:

- Use the GRADCamLogger callback during model training to visualize model progress using GradCAM.

### Fine-tuning the Model:

- After initial training with frozen layers, fine-tune the model by allowing all layers to be trainable.

### Model Evaluation:

- Evaluated the trained model using test data to assess its performance metrics such as accuracy, precision and recall.


### Results

- The trained model achieves competitive accuracy and performance metrics on the validation dataset.
GradCAM visualization helps understand the model's attention areas and aids in model interpretation.