# Tweet Sentiment Classifier

![image](https://github.com/Default-bit/tweets/assets/63794288/2d243cea-2368-45db-959e-9d08be2abcfb)

## Project Overview

- **Description**: This project is a Tweet Sentiment Classifier that utilizes machine learning techniques to analyze tweet sentiments. The classifier was built during the **Stanford Pre-Collegiate program**.
- **Project Components include:**
  - Data preprocessing
  - Model training
  - Evaluation
  - Sentiment prediction

## Project Goals

- **Objective**: The goal is to classify tweets into **positive** and **negative** sentiments.
- **Importance**: Sentiment analysis of tweets is crucial for understanding **public opinion**, **customer feedback**, and **social media trends**.
- **Methodology**: The classifier preprocesses tweet text, trains multiple models, and evaluates their performance to select the best model for sentiment prediction.


## Features

- Data Preprocessing: Cleaning and preparing tweet text for analysis.
- Model Training: Training multiple models including Logistic Regression, Naive Bayes, and SVM.
- Model Evaluation: Evaluating model performance using metrics and confusion matrices.
- Sentiment Prediction: Predicting the sentiment of new tweets.

## Setup

To get started with this project, follow these steps:

### Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab

### Installing Dependencies

Use the following commands to install the necessary packages:

```bash
pip install pandas numpy seaborn wordcloud matplotlib nltk scikit-learn
```

### NLTK Data
You will also need to download some NLTK data. Run the following code within your Python environment:
```bash
import nltk
nltk.download('wordnet')
```

## Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Default-bit/tweets.git
    ```
2. **Open the Jupyter Notebook or Google Colab and upload the .ipynb file.**
3. **Open the project in the Arduino IDE.**
4. **Run the cells in the notebook sequentially to preprocess data, train models, and evaluate their performance.**
5. **To predict the sentiment of a new tweet, use the predict function as demonstrated in the notebook.**

## Results

The performance of the models is evaluated using classification reports and confusion matrices. Below is an example confusion matrix for the Logistic Regression model:

![image](https://github.com/Default-bit/tweets/assets/63794288/976cec5c-e1c2-491f-95df-332d8142b383)

