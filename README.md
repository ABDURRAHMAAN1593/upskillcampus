# Crop vs Weed Image Classification using Custom CNN

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## Project Overview

This repository contains the implementation of a custom Convolutional Neural Network (CNN) for classifying crop and weed images. The project was developed during a 6-week internship at UpskillCampus as part of a group effort. This repository serves as a certification artifact and evaluation submission, containing the complete implementation and documentation of the project.

## Repository Contents

- `CropWeedDetection.ipynb`: Jupyter notebook containing the complete implementation of the custom CNN model
- `CropWeedDetection_Abdur_USC_UCT.pdf`: Detailed project report submitted for evaluation

## Dataset Information

The dataset used in this project was privately provided by UpskillCampus and is not included in this repository. However, the code implementation is publicly available and can be used as a reference for similar image classification tasks.

## How to Use

### Prerequisites

- Python 3.x
- TensorFlow 2.x
- Jupyter Notebook
- Required Python packages (install using pip):
  ```bash
  pip install tensorflow numpy pandas matplotlib scikit-learn
  ```

### Running the Notebook

1. Clone this repository
2. Open `CropWeedDetection.ipynb` in Jupyter Notebook
3. Run the cells sequentially to execute the model implementation

### Using Your Own Dataset

To use this implementation with your own dataset, organize your images in the following structure:

```
dataset/
├── train/
│   ├── crop/
│   │   └── (crop images)
│   └── weed/
│       └── (weed images)
└── test/
    ├── crop/
    │   └── (crop images)
    └── weed/
        └── (weed images)
```

- Supported image formats: .jpg, .png
- Ensure consistent image dimensions across your dataset
- Recommended minimum dataset size: 1000 images per class for training

## Model Architecture

The implementation uses a custom CNN architecture built from scratch using TensorFlow/Keras. The model includes:
- Multiple convolutional layers with ReLU activation
- MaxPooling layers for dimensionality reduction
- Dense layers for classification
- Dropout layers for regularization

## Note

This repository was created by one member of the project group for submission purposes. The implementation represents a collaborative effort during the UpskillCampus internship program.

## License

This project is open-source and available for reference and educational purposes. 
