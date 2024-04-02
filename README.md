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

## Usage

1. Install the required dependencies by running `pip install -r requirements.txt`.
2. Ensure that a pre-trained BERT model is available. You can specify the model name in the `answer_question_with_bert()` function or download it using the Hugging Face's model hub.
3. Provide a question and a passage of text to the `answer_question_with_bert()` function to get the answer.
4. Run the script and observe the extracted answer.
