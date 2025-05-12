# Sentiment-Analysis-Using-Hugging-Face-Transformers

# **Sentiment Analysis on Customer Reviews Using Hugging Face Transformers**

This project demonstrates sentiment analysis on customer reviews using Hugging Face's pre-trained **DistilBERT** model. The model is fine-tuned on the SST-2 dataset and is used to determine the sentiment of customer reviews, predicting whether the sentiment is positive or negative.

## **Project Overview**

The sentiment analysis pipeline analyzes a set of customer reviews, predicting whether the sentiment of each review is positive or negative, along with a confidence score. The sentiment is classified into one of two categories:

- **Positive**: When the review conveys a favorable sentiment.
- **Negative**: When the review conveys an unfavorable sentiment.

## **How to Use**

### Requirements

- Python 3.x
- Install the required libraries:
  ```bash
  pip install transformers
  
**Running the Code**
1. Clone this repository or open the provided Python script in your preferred editor.
2. Run the code in a Python environment.
3. You will be prompted to enter the number of sentences you want to analyze.
4. After providing the number of sentences, enter each sentence one by one.
5. The sentiment of each sentence will be analyzed, and the results will be displayed with the sentiment label (Positive/Negative) and confidence score.

Code Explanation
Importing Hugging Face's pipeline:
The pipeline function from Hugging Face's transformers library allows easy access to pre-trained models like DistilBERT for sentiment analysis.

Creating the Sentiment Analysis Pipeline:
The code initializes a sentiment analysis pipeline using a pre-trained DistilBERT model fine-tuned on the SST-2 dataset. This model is specifically designed for sentiment classification.

User Input for Sentences:
The program asks the user how many sentences they would like to analyze. Afterward, it prompts the user to input each sentence for sentiment analysis.

Sentiment Prediction:
The sentiment_analyzer pipeline analyzes the provided sentences and returns the sentiment classification (positive or negative) and a confidence score.

Displaying Results:
The program then prints the sentiment and the corresponding confidence score for each sentence.
