# Question Answering with BERT

This project implements a question answering system using BERT (Bidirectional Encoder Representations from Transformers) model from the Hugging Face's `transformers` library. Given a question and a passage of text, the system extracts the most relevant answer from the passage.

## Features

- Utilizes pre-trained BERT model fine-tuned for question answering tasks.
- Efficiently tokenizes and encodes input text using the transformers library.
- Provides accurate answers by identifying the most appropriate answer span within the passage.
- Handles errors gracefully through error handling mechanisms.

## Requirements

- Python 3.x
- `transformers` library
- `torch` library
- `nltk` library (for optional preprocessing steps)
