# Sentiment-Analysis

# Sentiment Analysis and Named Entity Recognition

This repository contains a Python script for performing sentiment analysis and named entity recognition (NER) on a dataset of reviews. The script uses various Natural Language Processing (NLP) techniques and models, including VADER and RoBERTa, to analyze sentiment and extract named entities from text data.

## Overview

The script performs the following tasks:
1. **Data Preparation**: Reads and preprocesses review data from a CSV file.
2. **Exploratory Data Analysis (EDA)**: Visualizes the distribution of review scores.
3. **Basic NLP**: Tokenizes text, performs part-of-speech tagging, and named entity recognition using NLTK.
4. **Sentiment Analysis**:
   - Uses VADER to analyze sentiment scores.
   - Uses RoBERTa, a transformer-based model, for sentiment analysis and compares it with VADER.
5. **Visualization**: Plots sentiment scores and compares results from VADER and RoBERTa.
6. **Model Comparison**: Analyzes and compares sentiment scores from different models.
7. **Transformers Pipeline**: Provides a quick way to run sentiment predictions using Hugging Face's `pipeline`.

## Installation

To run the script, you need to install the required Python libraries. You can install them using `pip`:

```bash
pip install pandas numpy matplotlib seaborn nltk transformers tqdm svgling
