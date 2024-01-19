# Fraudulent Detection Model

## Overview

This Python notebook demonstrates a fraudulent detection model developed for a dataset containing credit card transaction details. The dataset features were anonymized due to regulatory requirements, showcasing the ability to engineer relationships between various features and feed them into a neural network to learn patterns without knowing the specifics of the features. The model utilizes PyTorch and achieved a remarkable accuracy of 97.38% on the test set.

## Model Architecture

The model architecture consists of a feedforward neural network with configurable hidden layers and sizes. Each hidden layer employs a ReLU activation function, and the output layer is configured with a sigmoid activation to generate predictions. Specifically:

- **Hidden Layers:** 6 layers
- **Neurons per Hidden Layer:** 64
- **Learning Rate:** 1e-4

## Features

- **Anonymized Feature Engineering:** The model showcases the capability to engineer relationships between anonymized features, demonstrating the ability to learn patterns without explicit knowledge of individual feature meanings.
  
- **PyTorch Implementation:** Leveraging PyTorch, the model is implemented as a feedforward neural network with configurable hidden layers and sizes, providing flexibility in architecture design.

- **High Accuracy:** The model achieved a high accuracy of 97.38% on the unseen data(test set).

## Dependencies

- Python 3.x
- PyTorch
- pandas
- scikit-learn

Ensure the required packages are installed using:

```bash
pip install torch pandas scikit-learn

```

## Result

- **Test Set Accuracy:** 97.38%

## Acknowledgments

- Dataset source -- [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)

## License

This project is licensed under the [MIT License.](https://choosealicense.com/licenses/mit/)