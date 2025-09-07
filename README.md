# GRU-based-Next-Word-Predictor
A simple Next Word Prediction model using PyTorch GRU. Trained on a toy dataset, it predicts the next word in a sentence based on previous words.
📝 Project Description

This project implements a Next Word Prediction Model using PyTorch and a GRU (Gated Recurrent Unit) neural network.
The model is trained on a small toy dataset of sentences and learns to predict the next word given a sequence of previous words.

🔹 Features

Tokenization and vocabulary building with <PAD> and <UNK> tokens

Input-target sequence generation for language modeling

Sequence padding for variable-length inputs

GRU-based neural network for context learning

Training with CrossEntropyLoss and Adam optimizer

Simple prediction function to generate the next word after a given text seed

🔹 Example

Input:

"the cat"


Output:

Prediction after 'the cat': sat
