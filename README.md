
## Project Summary

In this project, you will learn how to build an AI chatbot using LSTMs, Seq2Seq, and pre-trained word embeddings for increased accuracy. You will be provided with a dataset of conversational dialogue. You will use this dataset to build your chatbot using Pytorch, train it on the dataset, and tune your network hyperparameters.

At the end of the project, you will demonstrate your proficiency in deep learning by conversing with their chatbot at the command line.



## Project Steps Overview

Below you will find each of the components of the project



### Prepare data

Build your vocabulary from a corpus of language data. The Vocabulary object is described in Lesson Six: Seq2Seq.

### Build Model

Build your Encoder, Decoder, and larger Sequence to Sequence pattern in PyTorch. This pattern is described in Lesson Six: Seq2Seq.

### Train Model

Write your training procedure and divide your dataset into train/test/validation splits. Then, train your network and plot your evaluation metrics. Save your model after it reaches a satisfactory level of accuracy.

### Evaluate & Interact w/ Model

Write a script to interact with your network at the command line.

## Project Summary

The LSTM Chatbot will help you show off your skills as a deep learning practitioner. You will develop the chatbot using a new architecture called a Seq2Seq. Additionally, you  **_can_**  use pre-trained word embeddings to improve the performance of your model. Let's get started by following the steps below:

## Step 1: Build your Vocabulary & create the Word Embeddings

-   The most important part of this step is to create your Vocabulary object using a corpus of data drawn from TorchText.

(Extra Credit)

-   Use Gensim to extract the word embeddings from one of its corpus'.
-   Use NLTK and Gensim to create a function to clean your text and look up the index of a word's embeddings.

## Step 2: Create the Encoder

-   A Seq2Seq architecture consists of an encoder and a decoder unit. You will use Pytorch to build a full Seq2Seq model.
-   The first step of the architecture is to create an encoder with an LSTM unit.

(Extra Credit)

-   Load your pretrained embeddings into the LSTM unit.

## Step 3: Create the Decoder

-   The second step of the architecture is to create a decoder using a second LSTM unit.

## Step 4: Combine them into a Seq2Seq Architecture

-   To finalize your model, you will combine the encoder and decoder units into a working model.
-   The Seq2Seq2 model must be able to instantiate the encoder and decoder. Then, it will accept the inputs for these units and manage their interaction to get an output using the forward pass function.

## Step 5: Train & evaluate your model

-   Finally you will train and evaluate your model using a Pytorch training loop.

## Step 6: Interact with the Chatbot

-   Demonstrate your chatbot by converting the outputs of the model to text and displaying it's responses at the command line.
