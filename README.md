# Contextual Bank Disambiguation

This project explores the disambiguation of the word "bank" in text, determining whether it refers to a financial institution or a riverbank, based on sentence context. The primary goal is to evaluate how different levels of contextual information (high-context vs. low-context sentences) affect the accuracy of a machine learning model's predictions.

## Project Description

In natural language, many words have multiple meanings. This project aims to classify the meaning of the word "bank" in text by training a machine learning model to distinguish between two primary meanings: 
1. **Financial Bank** (institutional)
2. **River Bank** (geographical feature)

### Key Components:
- **Text Classification:** Disambiguating the word "bank" using natural language processing (NLP) techniques.
- **Contextual Analysis:** Testing the model's performance in high-context vs. low-context sentences, where the clarity of the word "bank" varies.
- **Machine Learning Model:** A binary classification model built using a neural network that processes text data to predict the meaning of "bank."
- **Performance Evaluation:** Comparison of the model's performance in different contextual settings to see how sentence ambiguity influences accuracy.

### Results
- **High-context accuracy:** 91%
- **Low-context accuracy:** 46%

These results show that the model relies heavily on strong contextual cues to correctly classify the meaning of "bank," highlighting its strengths in clear scenarios and weaknesses in ambiguous ones.

## Skills Involved

- **Natural Language Processing (NLP):** Preprocessing and tokenizing text data for input into a neural network.
- **Machine Learning:** Building and training a neural network model for binary classification.
- **Contextual Language Understanding:** Evaluating how varying sentence contexts affect the model’s performance in handling ambiguous words.
- **Python Programming:** Utilization of Python libraries such as TensorFlow/Keras for model building and data processing.
- **Evaluation Metrics:** Measuring model performance through accuracy in high-context vs. low-context settings.
