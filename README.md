# Aspect-Based Sentiment Analysis of Customer Reviews
  Enhanced Product Feedback Insights

* Project Overview

This project develops an Aspect-Based Sentiment Analysis (ABSA) framework to extract more granular and actionable insights from customer reviews. Instead of assigning a single overall sentiment to a review, the approach identifies specific product aspects (e.g. features, services) and determines the sentiment associated with each aspect.

The project was completed as part of my MSc dissertation and has been adapted here as a portfolio-ready NLP project.

* Problem Statement

Traditional sentiment analysis provides limited value for product improvement because it does not explain which aspects customers are responding to positively or negatively. This project addresses that limitation by:

Automatically identifying key aspects mentioned in customer reviews

Classifying sentiment at the aspect level

Enabling more precise identification of customer pain points and strengths

* Methodology

The ABSA pipeline consists of two fine-tuned transformer-based models:

Aspect Extraction:
A fine-tuned BERT model was used to identify and extract product aspects mentioned in customer reviews, such as features and services.

Aspect-Level Sentiment Classification:
A fine-tuned RoBERTa model was used to classify the sentiment associated with each extracted aspect.

This two-stage approach allows sentiment to be analysed at a much finer granularity than document-level sentiment classification.

<!-- Model Performance

BERT (Aspect Extraction):

Precision: 0.9740

F1 Score: 0.9731

RoBERTa (Sentiment Classification):

Precision: 0.8194

F1 Score: 0.7993

The results demonstrate strong performance in identifying relevant aspects and reasonably robust sentiment classification at the aspect level.-->

* Key Outcomes

Enabled detailed analysis of customer feedback beyond overall sentiment

Identified specific product pain points and areas for improvement

Demonstrated how ABSA can support data-driven product development and customer service strategies

* Tech Stack

Language: Python

NLP Models: BERT, RoBERTa

Libraries: Hugging Face Transformers, PyTorch, scikit-learn

Data Processing: pandas, NumPy

Tools: Colab Notebook, Git

\* Notes

This repository is intended to demonstrate:

Applied NLP for real-world customer feedback analysis

Structured machine learning experimentation

Reproducible and interpretable sentiment analysis pipelines
