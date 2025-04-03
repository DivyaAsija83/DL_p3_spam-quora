Quora Spam Detection Model

Project Overview

This project aims to build a machine learning model to identify whether a question posted on Quora is spam or not. The model leverages pre-trained word embeddings and NLP techniques to improve classification accuracy.

Dataset

The dataset contains Quora questions labeled as spam or not spam. It also includes GloVe embeddings, which can be used to reduce dimensionality and improve performance.

Suggested Guidelines

Dimensionality Reduction: Used the provided GloVe embeddings to bring down the dimensions of the model.

Pre-trained Embeddings: Utilize pre-trained word embeddings as outlined in the Keras blog.

Train/Validation Splits: Maintain and create custom train-validation splits from the full dataset for better generalization.

Installation

To set up the project, follow these steps:

# Clone the repository
git clone https://github.com/yourusername/quora-spam-detection.git
cd quora-spam-detection

# Install required dependencies
pip install -r requirements.txt

Usage

Run the following command to train the model:

python train.py

To evaluate the model:

python evaluate.py

Model Architecture

Word Embeddings: GloVe pre-trained vectors

Feature Engineering: NLP-based text processing

Classifier: LSTM/CNN/Transformer-based model

Results

Model performance metrics such as accuracy, precision, recall, and F1-score will be updated after model training.

Contributing

If you'd like to contribute, feel free to fork the repository and submit a pull request with improvements.

License

This project is licensed under the MIT License.
