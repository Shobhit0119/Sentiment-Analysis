# Sentiment Analysis

This repository contains a sentiment analysis project that aims to classify text data into positive, negative, or neutral sentiments.

## Dataset

The project uses the [IMDB dataset](https://ai.stanford.edu/~amaas/data/sentiment/) for training and evaluation. The dataset consists of 50,000 movie reviews labeled as positive or negative.

## Models

The following models are implemented:

- **Logistic Regression**: A simple linear model for binary classification.
- **Support Vector Machine (SVM)**: A linear classifier that finds the optimal hyperplane for separating classes.
- **Recurrent Neural Network (RNN)**: A neural network that captures sequential information in data.
- **Long Short-Term Memory (LSTM)**: An improved version of RNN that addresses the vanishing gradient problem.

## Requirements

To run the code in this repository, install the following dependencies:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras

You can install the required packages using pip:

```bash
pip install numpy pandas scikit-learn tensorflow keras

Usage

1: Clone the repository:

git clone https://github.com/Shobhit0119/Sentiment-Analysis.git

Navigate to the project directory:

cd Sentiment-Analysis


Run the desired model script. For example, to run the Logistic Regression model:

python logistic_regression.py
Similarly, you can run other models by executing their respective scripts.

Results

The performance of each model is evaluated using accuracy and F1-score. The results are summarized below:

Model	Accuracy	F1-Score
Logistic Regression	85%	0.84
SVM	86%	0.85
RNN	88%	0.87
LSTM	90%	0.89

Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

License
This project is licensed under the MIT License. See the LICENSE file for details.



