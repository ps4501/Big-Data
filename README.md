# Big-Data
# Natural Language Processing Projects

## Table of Contents
1. [Introduction](#introduction)
2. [Text Classification and Sentiment Analysis](#text-classification-and-sentiment-analysis)
    - [Overview](#overview)
    - [Installation](#installation)
    - [Usage](#usage)
3. [Question and Answer Retrieval System](#question-and-answer-retrieval-system)
    - [Overview](#overview-1)
    - [System Architecture](#system-architecture)
    - [Usage](#usage-1)
4. [Contributors](#contributors)
5. [License](#license)

## Introduction
This repository contains two main projects related to Natural Language Processing (NLP):
1. **Text Classification and Sentiment Analysis**: A project focusing on categorizing text data and determining sentiment polarity.
2. **Question and Answer Retrieval System**: A system designed to retrieve answers to user queries from a dataset of news articles.

## Text Classification and Sentiment Analysis

### Overview
This project involves building models to classify text data into predefined categories and analyze the sentiment of the text. The main goal is to implement and evaluate various machine learning algorithms to achieve high accuracy in text classification and sentiment analysis tasks.

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/ps4501/Big-Data.git
    cd your-repo
    ```
2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

### Usage
1. Open the Jupyter Notebook `Text_classification_and_sentiment_analysis.ipynb` to explore the code and execute the cells.
2. Follow the instructions within the notebook to preprocess the data, train the models, and evaluate their performance.

## Question and Answer Retrieval System

### Overview
This project focuses on developing a Question Answering (QA) system capable of retrieving accurate answers from a dataset of news articles. The system leverages state-of-the-art NLP models such as BERT to understand and answer user queries effectively.

### System Architecture
The QA system follows a structured approach:
1. **Data Preprocessing**: Cleaning and preparing the text data for analysis.
2. **Entity Extraction**: Identifying key entities in the text for efficient retrieval.
3. **Vectorization**: Transforming text into numerical representations using TF-IDF.
4. **Cosine Similarity**: Measuring similarity between user queries and text segments to find relevant answers.
5. **Question Answering**: Utilizing a pre-trained BERT model to extract the most relevant answer spans from the text.

### Usage
1. Prepare the environment by installing the necessary packages:
    ```sh
    pip install -r requirements.txt
    ```
2. Run the main script to start the QA system:
    ```sh
    python main.py
    ```
3. Interact with the system by entering your queries. The system will return the most relevant answers from the dataset.

## Contributors
- Haider Ali Lokhand [a1894658]
- Paridhi Awadheshpratap Singh [a1865487]
- Chahat Segan [a1855353]

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
