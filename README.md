# AI-Powered-Headline-Generator-Using-LSTM-and-Transformers

A deep learning-based headline generation model built using LSTM and Transformer architectures. This project utilizes a Streamlit-powered interface for real-time text input and headline generation. Trained on a cleaned Kaggle news dataset.

## Overview

This project explores natural language generation (NLG) techniques to automatically generate concise and relevant headlines from input news content. The core model is based on a hybrid approach using **LSTM layers** and **Transformer encoders** to understand context and generate human-like headlines.

## Dataset

- **Source:** [Combined News Headlines Dataset](https://drive.google.com/file/d/1OImU4gEL5PdTR_PDvCgP8H_LzI5KHNYg/view?usp=drive_link)  
- Preprocessing included tokenization, truncation, stopword removal, and padding.

## Features

- Encoder-Decoder architecture using LSTM and Transformer layers
- Streamlit GUI for user-friendly interaction
- Real-time headline prediction from input news text
- Ability to retrain or test on new datasets
- Integrated tunnel support for public sharing via ngrok

## Tech Stack

- **Python 3.x**
- **TensorFlow / Keras**
- **NLTK / spaCy** for NLP preprocessing
- **Streamlit** for GUI interface
- **Ngrok** for sharing Streamlit tunnel
- **Pandas / NumPy / Matplotlib** for data handling and visualization

## How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
