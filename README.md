# Fake News

A logistic classification model that classifies articles into fake and reliable. 

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Data files](#data-files)
4. [File Descriptions](#file-descriptions)
5. [Running the Notebooks](#running-the-notebooks)


---

## Project Overview

A project utilizing logistic regression for classifying news articles as reliable or fake typically involves several key steps. It begins with text preprocessing, which includes cleaning the data, tokenization, and vectorization to convert text into numerical format. 
The logistic regression model is then trained on this processed data, and evaluation metrics such as accuracy, precision, recall, and F1 score are used to assess its performance in detecting misinformation.

---

## Prerequisites

Before you start, ensure you have the following installed:

- Python 3.12
- Jupyter Notebook or JupyterLab

## Data Files

For the program to work, the data needs to be downloaded and placed in the same directory as the rest of the other files. 
You can get the Fake News Corpus subset in the link below:
https://raw.githubusercontent.com/several27/FakeNewsCorpus/master/news_sample.csv 
All other data files are in the respiratory
([Scraped data]CBS_bbc_scraped_articles.csv, [test data](test.tsv) and the Fake News corpus)

## File description 

[Part1Task1](Part1Task1.ipynb) This file cleans, tokenizes and stemmes a subset of the whole dataset. 
[Part1Task2](Part1Task2.ipynb) This file preprocesses the entire Fake News Corpus. 
[Part1Task3](Part1Task3.ipynb) This file distributes the preprocessed data. 
[Part1Task4](Part1Task4.ipynb) This file splits the data set into training, validation and test data. 
[Part2Task1-3](Part2Task1-3.ipynb) This file designs a simple logistic regression model which is trained with training data and evaluated in both validation and test, together with a performance evaluation on LIAR dataset. 
[Part3](Part3.ipynb) This file designs an advanced logistic regression with feature engineering and grid searchCV. The model is then trained with training data and testes with validation and test data. The model is also evaluated in with a peformance measure on the LIAR dataset. 
[Part4Task2](Part4Task2.ipynb) This file contains LIAR dataset and preprocesses it together with an evaluation with the advanced model. 

## Running the Notebooks
The order which the notebooks should be run is showed below. 
1. Download and place all the required files in the same directory before running the Notebooks
2. (Part1Task1.ipynb)
3. (Part1Task2.ipynb)
4. (Part1Task3.ipynb)
5. (Part1Task4.ipynb)
6. (Part2Task1-3.ipynb)
7. (Part3.ipynb)
8. (Part4Task2.ipynb)
