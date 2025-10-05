
# Fake News Detection System

A deep learning project that detects fake news articles using an LSTM model built with TensorFlow. The system processes news text with NLP techniques like tokenization and word embeddings and trains a Long Short-Term Memory (LSTM) network for classification.

## Features

  * Preprocesses raw text using tokenization and word embeddings.
  * Implements a Long Short-Term Memory (LSTM) neural network in TensorFlow/Keras.
  * Classifies news articles with high accuracy.
  * Visualizes data with word clouds to identify common words in fake and real news.
  * Easy to extend with other datasets or models.

## Dataset

This project uses the "Fake and real news dataset" which contains two CSV files:

  * `Fake.csv`: Contains fake news articles.
  * `True.csv`: Contains real news articles.

Each dataset includes the title, text, subject, and date of the news articles.

## Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Navbaloo/Fake-news-detection-system.git
    ```
2.  Install the required libraries:
    ```bash
    pip install pandas seaborn matplotlib wordcloud scikit-learn tensorflow
    ```

## Usage

1.  Open the `Fake_News_Detection.ipynb` notebook in a Jupyter environment.
2.  Run the cells in the notebook sequentially to train the model and see the results.

## Model Architecture

The model is a sequential neural network with the following layers:

1.  **Embedding Layer**: Creates dense vectors from integer-encoded text.
2.  **LSTM Layer**: A type of recurrent neural network (RNN) that can learn long-term dependencies.
3.  **Dense Layers**: Fully connected layers for classification.

## Results

The LSTM model achieves high accuracy in classifying news articles as fake or real. The specific accuracy can be found by running the notebook.
