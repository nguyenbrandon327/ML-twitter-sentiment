# Twitter Sentiment Analysis Project

👋 This is my Twitter Sentiment Analysis project! 

## What is this?

In this project, I've implemented a simple yet powerful linear neural network that analyzes tweets and predicts their **happiness intensity**. I'm using pretrained embeddings from HuggingFace's Transformers library to convert text into meaningful vector representations, then training a model to predict how joyful the content is on a scale.

## Key Features

- Uses PyTorch to build and train the neural network
- Leverages pretrained embeddings from `sentence-transformers/all-MiniLM-L6-v2`
- Implements an analytical solution for training rather than gradient descent
- Analyzes real tweets with their associated happiness scores
- Includes regularization to prevent overfitting

## Why?

This project has been an amazing opportunity to apply machine learning to understand human emotions expressed in text. It's fascinating to see how well a relatively simple model can capture the nuances of happiness in short text snippets.

## Getting Started

If you want to try it yourself, just clone this repo and open the Jupyter notebook. You'll need PyTorch, HuggingFace Transformers, pandas, and matplotlib installed.
