# SP25-690-Tadikamalla
# Hotel Sentiment Analysis Using Deep Learning Models

## Overview
This project implements and compares multiple machine learning and deep learning models for sentiment analysis of online reviews.

## Features
- IMDb movie review sentiment classification
- TF-IDF + Logistic Regression baseline model
- Embedding-based Neural Network
- LSTM model
- Bidirectional LSTM
- Optional DistilBERT transformer model
- Real-time Google review sentiment prediction

## Dataset
- IMDb Movie Review Dataset
- 50,000 reviews
- Binary sentiment classification

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| TensorFlow / Keras | Deep learning implementation |
| Scikit-learn | Baseline ML model and evaluation |
| Pandas | Data processing |
| Matplotlib | Visualization |
| Google Places API | Real-world review extraction |

## Experimental Results

| Model | Accuracy | F1-score |
|---|---:|---:|
| TF-IDF + Logistic Regression | 87.94% | 87.94% |
| Embedding + Global Average Pooling | 87.14% | 87.14% |
| Bidirectional LSTM | 83.09% | 82.97% |
| LSTM | 51.93% | 44.00% |

## Future Improvements
- Hotel-specific sentiment datasets
- Multilingual sentiment analysis
- Transformer fine-tuning

## Author
Developed as part of a Deep Learning course project by Venkata Sai Sudeep Tadikamalla.
