# Legal-Case-Text-Summarization


This project is an application of natural language processing techniques to the task of summarizing legal case texts. We experimented with five different algorithms: BERT, Neural Network, SumBasic, KL Divergence, and TextRank. Our goal was to compare the performance of these algorithms in terms of their ability to generate accurate and concise summaries of legal cases.

## Data

We used a dataset of 4,000 legal cases obtained from https://archive.ics.uci.edu/ml/datasets/Legal+Case+Reports. The dataset was preprocessed and cleaned to remove irrelevant information such as metadata and formatting, as well as to ensure consistency in the formatting of the case texts.

## Algorithms

We implemented five algorithms for legal case text summarization:

BERT
Neural Network
SumBasic
KL Divergence
TextRank

## Evaluation

We used the ROUGE metric to evaluate the performance of each algorithm. Specifically, we used ROUGE-1, ROUGE-2, and ROUGE-L, which measure the overlap between the generated summary and the reference summary in terms of unigrams, bigrams, and the longest common subsequence, respectively.
