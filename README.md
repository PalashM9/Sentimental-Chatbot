# Sentimental Chatbot

This Python script provides a sentimental chatbot that uses machine learning models to analyze the sentiment of a user's input and generate a relevant response.

## Features

- **Sentiment Analysis:** The chatbot uses the `distilbert-base-uncased-finetuned-sst-2-english` and `monologg/bert-base-cased-goemotions-original` models for sentiment analysis.
- **Conversational Responses:** It utilizes the `microsoft/DialoGPT-medium` model for generating conversational responses based on the detected sentiment.

## How It Works

1. The script first sets up pipelines for sentiment analysis and conversational response generation.
2. When a user inputs text, the script uses sentiment analysis models to determine the sentiment of the input.
3. The chatbot then generates a response considering the detected sentiment.
4. The conversation continues until the user types 'quit'.

## Requirements

- Python 3.x
- Transformers library
- IPython
- A pre-trained BERT model from Hugging Face's model repository

## Usage

1. Start the script.
2. Type your message to the chatbot and press Enter.
3. The chatbot will respond considering the sentiment of your message.
4. Type 'quit' to end the conversation.
