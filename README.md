# movie-sentiment-predictor
Analyze IMDB reviews using SimpleRNN in Keras. Delve into NLP and ML. Predict sentiments, grasp deep learning with real data. Explore sentiment understanding via neural networks.


# Sentiment Analysis with SimpleRNN

This project demonstrates sentiment analysis on the IMDB movie reviews dataset using a SimpleRNN model in Keras.

## Dataset
The IMDB movie reviews dataset is used for sentiment analysis. It consists of movie reviews labeled as positive or negative.

## Model Architecture
- The model uses an Embedding layer followed by a SimpleRNN layer and a Dense layer with sigmoid activation for binary classification.
- The model is trained using binary cross-entropy loss and the RMSprop optimizer.

## Usage
1. Load the IMDB dataset and preprocess the data.
2. Define and compile the SimpleRNN model.
3. Train the model on the training data and evaluate it on the test data.
4. Save the model weights to 'model_weights.h5'.
5. Use the `predict_sentiment` function to predict the sentiment of input text.

## Files
- `movie-sentiment-predictor.ipynb`: Jupyter Notebook containing the code.
- `model_weights.h5`: Saved model weights.
- `README.md`: Project description and usage instructions.

## Requirements
- Python 3
- NumPy
- Keras
- TensorFlow

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run the `movie-sentiment-predictor.ipynb` notebook.

