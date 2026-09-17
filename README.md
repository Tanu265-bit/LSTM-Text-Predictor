# LSTM Text Predictor 🧠

A Natural Language Processing (NLP) project that uses an LSTM (Long Short-Term Memory) neural network to predict the next word in a given text sequence.

## 📌 Project Overview

This project demonstrates next-word prediction using LSTM.

The model is trained on FAQ-based text data. Given a starting sentence, the model predicts the next word and can continue generating text.

### Example

**Input:**

`the total duration of the course is`

**Predicted next word:**

`7`

**Generated Text:**

`the total duration of the course is 7 months so the total course fee becomes 799 7 rs 5600 approx`

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Natural Language Processing (NLP)
- LSTM
- Word Tokenization

## 🧠 Model Architecture

```text
Input Text
    ↓
Tokenization
    ↓
Sequence Generation
    ↓
Padding
    ↓
Embedding Layer
    ↓
LSTM Layer (150 units)
    ↓
LSTM Layer (150 units)
    ↓
Dense Layer
    ↓
Softmax
    ↓
Next Word Prediction
