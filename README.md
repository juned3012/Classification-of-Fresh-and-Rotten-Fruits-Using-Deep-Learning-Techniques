# Classification of Fresh and Rotten Fruits Using Deep Learning Techniques

Welcome to the **FruitFreshnessClassifier** project, where we utilize deep learning techniques to distinguish between fresh and rotten fruits. This project focuses on classifying apples, bananas, and oranges into their respective categories of freshness.

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Model Optimization](#model-optimization)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Classifying fresh and rotten fruits accurately is essential for ensuring food quality and safety. This project employs deep learning techniques to build a robust classification system for apples, bananas, and oranges.

## Project Overview

This project includes:
- Data preprocessing and augmentation
- Implementation of three deep learning models: Convolutional Neural Network (CNN), VGG16, and ResNet50
- Model training and evaluation
- Model comparison and selection

## Data

The dataset used in this project is sourced from Kaggle and contains approximately 5,989 images of apples, bananas, and oranges, categorized as fresh or rotten.

## Preprocessing

The dataset was preprocessed using the following techniques:
- Data augmentation to increase the diversity of the training set
- Resizing images to a uniform size
- Normalization to scale pixel values

## Model Architecture

Three deep learning models were employed for classification:
- **Convolutional Neural Network (CNN)**: Custom CNN architecture designed for intricate feature extraction.
- **VGG16**: Pre-trained model known for its depth and performance in image classification tasks.
- **ResNet50**: Pre-trained model known for its residual learning capabilities.

## Results

The models were evaluated using accuracy as the primary metric. The CNN model demonstrated superior performance with an accuracy of 96.78%, effectively classifying fresh and rotten fruits.

## Model Optimization

To enhance model performance, techniques such as hyperparameter tuning, data augmentation, and regularization were applied. The CNN model's architecture was fine-tuned to achieve optimal results.

## Conclusion

The FruitFreshnessClassifier project successfully distinguishes between fresh and rotten fruits with high accuracy. The custom CNN model's performance highlights its capability for detailed feature extraction, making it a reliable choice for this classification task.

## Future Work

Future enhancements to this project could include:
- Integration with larger and more diverse datasets
- Deployment of the model as a web application for real-time classification
- Further exploration of advanced deep learning architectures
- Implementation of explainability techniques to understand model predictions better

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/juned3012/FruitFreshnessClassifier.git
    ```

2. Navigate to the project directory:
    ```sh
    cd FruitFreshnessClassifier
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To train and evaluate the models, run the `Fruit_Classification.ipynb` notebook. Ensure you have the necessary data files in the appropriate directories.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
