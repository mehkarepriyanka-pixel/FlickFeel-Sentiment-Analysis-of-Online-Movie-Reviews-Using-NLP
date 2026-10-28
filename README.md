# FlickFeel – Sentiment Analysis of Online Movie Reviews Using NLP

## Project Overview

FlickFeel is an NLP-based sentiment analysis project that analyzes
IMDb movie reviews and classifies them as Positive or Negative.

## Technologies Used

- Python
- NLP
- Pandas
- NumPy
- Scikit-learn
- Transformers
- DistilBERT
- PyTorch
- Streamlit
- Jupyter Notebook

## Project Workflow

IMDb Reviews
      ↓
Text Preprocessing
      ↓
Train/Test Split
      ↓
DistilBERT Tokenization
      ↓
Model Training
      ↓
Sentiment Classification
      ↓
Model Evaluation
      ↓
Streamlit Application

## Model

DistilBERT was used for sentiment classification because it provides
strong contextual understanding while being more lightweight than BERT.

## Result

The model achieved approximately 92% accuracy.

## Sentiment Classes

- Positive
- Negative

## Application

The trained model can be deployed through Streamlit to allow users
to enter a movie review and receive a sentiment prediction.
