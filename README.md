# Sentiment Analysis and Named Entity Recognition

This repository contains a Python script for performing sentiment analysis and named entity recognition (NER) on a dataset of Amazon fine food reviews. The script uses various Natural Language Processing (NLP) techniques and models, including VADER and RoBERTa, to analyze sentiment and extract named entities from text data.

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

## Usage

1. **Prepare the Data**:
   - Ensure you have a CSV file named `Reviews.csv` in the working directory. This CSV file should include at least two columns: `Text` (the review text) and `Score` (the review rating).

2. **Run the Script**:
   - Execute the Python script to perform sentiment analysis and named entity recognition. The script will read the data, analyze sentiment using both VADER and RoBERTa models, and generate visualizations.

   ```bash
   python amazon_sentiment_analysis.py



## Acknowledgments

This project builds on various tools and resources for sentiment analysis and named entity recognition. Special thanks to the following contributors and resources:

- **Rob Mulla**: The code and techniques used in this project were inspired by Rob Mulla's tutorial on sentiment analysis. For a detailed walkthrough and additional examples, please refer to Rob Mulla's YouTube video: [Sentiment Analysis Tutorial](https://youtu.be/QpzMWQvxXWk?feature=shared).

- **NLTK (Natural Language Toolkit)**: This library provides functionalities for text processing, including tokenization, part-of-speech tagging, and named entity recognition. For more information, visit the [NLTK website](https://www.nltk.org/).

- **VADER Sentiment Analysis**: VADER is a sentiment analysis tool included in NLTK that is specifically designed for social media text. More details can be found in the [NLTK VADER documentation](https://www.nltk.org/_modules/nltk/sentiment/vader.html).

- **Transformers Library by Hugging Face**: The RoBERTa model used in this project comes from Hugging Face's Transformers library, which provides state-of-the-art pre-trained models for a variety of NLP tasks. Learn more about RoBERTa and other models at the [Hugging Face model page](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment) and the [Transformers documentation](https://huggingface.co/transformers/).

- **Scipy**: Used for the `softmax` function, which converts raw scores into probabilities. Find more information at the [SciPy documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.special.softmax.html).

- **Seaborn** and **Matplotlib**: These libraries were used for data visualization, creating various plots to analyze sentiment scores. Visit the [Seaborn documentation](https://seaborn.pydata.org/) and [Matplotlib documentation](https://matplotlib.org/stable/contents.html) for more details.

- **TQDM**: This library provides progress bars for loops, making it easier to monitor the progress of long-running tasks. Check out the [TQDM documentation](https://tqdm.github.io/) for more information.

Thank you to the open-source community for providing these valuable tools and resources that made this project possible.

