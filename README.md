# Gender Classification using ResNet-50 and ResNet-101

![GitHub](https://github.com/cyongkypranowo/DeepLearning-Gender-CLassification)

This repository contains the implementation of gender classification using ResNet-50 and ResNet-101 architectures. The models are trained on the CelebA dataset, which consists of labeled facial images, for predicting the gender of individuals based on their facial images.

## Overview

Gender classification is a common task in computer vision applications. This project explores the development of gender classification models using deep learning techniques. ResNet-50 and ResNet-101 architectures are employed due to their effectiveness in handling image data and extracting features.

## Key Features

- Implementation of ResNet-50 and ResNet-101 architectures for gender classification.
- Training on the CelebA dataset, which includes labeled facial images.
- Evaluation metrics such as accuracy and confusion matrix provided for model assessment.
- Sample predictions and visualizations included for better understanding.

## Installation

1. Clone the repository:
git clone https://github.com/cyongkypranowo/DeepLearning-Gender-CLassification.git

2. Install the required dependencies:
pip install -r requirements.txt

## Usage

1. Prepare your dataset or use the provided CelebA dataset.
2. Train the models by running the respective scripts: `train_resnet50.py` and `train_resnet101.py`.
3. Evaluate the trained models using the evaluation scripts: `evaluate_resnet50.py` and `evaluate_resnet101.py`.
4. Make predictions on new images using the trained models with the inference scripts: `predict_resnet50.py` and `predict_resnet101.py`.

## Results

The performance of the models can be evaluated using various metrics such as accuracy, precision, recall, and F1-score. Additionally, confusion matrices and sample predictions are provided to assess the model's performance visually.

## Contributing

Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
