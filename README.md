# Natural Language Processing (NLP) Notebook

This repository contains a Python notebook that performs basic Natural Language Processing (NLP) tasks and Exploratory Data Analysis (EDA) on a text dataset.

## Overview

The main steps executed in the notebook are as follows:

1. **Data Loading and Exploration**: The notebook begins by loading the text data into a pandas DataFrame. It then performs initial exploration to understand the structure and content of the data.

2. **Text Preprocessing**: The text data is preprocessed using several techniques such as lowercasing, whitespace removal, stopword removal, and punctuation removal.

3. **Text Normalization**: The text data is further normalized using lemmatization, which reduces words to their base or root form.

4. **Feature Extraction**: The Term Frequency-Inverse Document Frequency (TF-IDF) is calculated for each word in the document. TF-IDF reflects how important a word is to a document in a collection or corpus.

5. **Visualization**: The top 20 words with the highest TF-IDF scores are displayed. This gives an idea of the most significant words in the text data.

By the end of the notebook, we have a clean and normalized text dataset, with insights into the most significant words in the corpus. This processed data can be used as input for various NLP tasks such as topic modeling, text classification, sentiment analysis, etc.

## Requirements

The notebook requires Python and the following Python libraries installed:

- NumPy
- pandas
- matplotlib
- NLTK
- sklearn
- re

## Usage

To run the notebook, you'll need to have Jupyter installed on your computer. You can then start the notebook server from the command line (using Terminal on Mac/Linux, Command Prompt on Windows) by running:

```bash
jupyter notebook
```

This will print some information about the notebook server in your terminal, including the URL of the web application (by default, `http://localhost:8888`). It will then open your default web browser to this URL.

Once the Jupyter Notebook is running, navigate to the repository folder and open the `.ipynb` notebook file. Follow the instructions in the notebook.
