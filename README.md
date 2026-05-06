# Sentiment Analysis on Movie Reviews

##  Description

This project builds a deep learning model to classify movie reviews as **positive** or **negative** using Natural Language Processing (NLP).

The model is trained on the IMDB dataset and uses an LSTM (Long Short-Term Memory) neural network to understand and analyze textual data.

---

## Features

* Text preprocessing (cleaning, removing HTML, normalization)
* Tokenization and sequence padding
* Deep learning model using Bidirectional LSTM
* Train/test split and model evaluation
* Predict sentiment for custom input text
* Confidence score for predictions

---

## Technologies Used

* Python
* TensorFlow / Keras
* Pandas & NumPy
* Scikit-learn

---

## Dataset

* IMDB Movie Reviews Dataset
* Contains 50,000 labeled reviews (positive / negative)

---

## Model Architecture

* Embedding Layer (input_dim=10000, output_dim=128)
* Bidirectional LSTM (64 units)
* Dropout layers for regularization
* Dense output layer with sigmoid activation

---

## How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

2. Make sure the dataset file is in the same directory:

```bash
IMDB Dataset.csv
```

3. Run the script:

```bash
python your_file_name.py
```

---

## Model Evaluation

* Uses binary classification (Positive / Negative)
* Evaluated on test data after training
* Includes early stopping to prevent overfitting

---

##Testing

The project includes:

* Manual test sentences
* Random samples from dataset
* Prediction with confidence score

Example:

```text
Text: This movie was amazing!
Prediction: Positive | Confidence: 0.95
```

---

## Use Cases

* Review analysis
* Social media sentiment detection
* Customer feedback analysis
* NLP learning projects
