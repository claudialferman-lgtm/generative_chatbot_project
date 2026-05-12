# generative_chatbot_project
A deep learning chatbot project built with TensorFlow and Keras using real Twitter conversation data focused on weather-related tweets. This project demonstrates how to train a sequence-to-sequence (seq2seq) generative chatbot capable of producing conversational responses based on user input.

## Project Overview

This project was completed as part of the Off-Platform Project: Generative Chatbot. Instead of using movie dialogue datasets, the chatbot was trained using real Twitter response pairs extracted from weather.txt.

The chatbot learns conversational patterns from weather-related discussions and generates responses using a trained encoder-decoder neural network architecture.

## Features
- Preprocesses Twitter conversation data into response pairs
- Builds and trains a seq2seq chatbot model
- Uses one-hot encoded token sequences
- Generates responses interactively through the terminal
- Supports conversational exit commands
- Trained specifically on weather-related tweet data

## Technologies Used
- Python 3
- TensorFlow
- Keras
- NumPy
- Regular Expressions (re)

## Dataset
The chatbot was trained using:
weather.txt

This file contains grouped Twitter response pairs related to weather conversations. Each pair consists of:
- An initial tweet
- A reply tweet

These response pairs are used to train the chatbot conversationally.
