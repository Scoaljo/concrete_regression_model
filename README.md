# Concrete Strength Prediction using Neural Networks
This project explores the use of neural networks to predict concrete compressive strength based on various input features. It demonstrates the application of different machine learning techniques and model architectures to improve prediction accuracy.

## Project Overview
The goal of this project is to predict the compressive strength of concrete using a dataset that includes various features such as cement content, water content, and age. We use neural networks implemented with Keras to build and compare different models.

## Key Features

- Data preprocessing and normalization
- Implementation of neural networks using Keras
- Exploration of different model architectures
- Comparison of model performance across various experiments

## Experiments
The project includes four main experiments:

- **Baseline Model**: A simple neural network with one hidden layer.
- **Normalized Data**: Using normalized input data to improve model convergence.
- **Increased Epochs**: Training the model for a longer period (100 epochs instead of 50).
- **Complex Model**: A deeper neural network with three hidden layers.

## Results
The project demonstrates how different techniques affect the model's performance:

- Data normalization unexpectedly increased the Mean Squared Error (MSE).
- Increasing the number of training epochs significantly improved performance.
- The complex model with multiple hidden layers achieved the best results.

## Technologies Used

- Python
- Keras (TensorFlow backend)
- NumPy
- Pandas
- Scikit-learn

## Contributing
Contributions to this project are welcome! Please feel free to submit a Pull Request.

## License
This project is open source and available under the MIT License.