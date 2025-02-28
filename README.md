# DM2024-Lab2-Homework
## Lab Report: Emotion Classification on Tweets

This repository contains the lab report for an emotion classification project on tweets. The full, detailed report is available in the attached PDF. Below is a brief overview of the key steps and findings:

### Overview

- **Data Exploration:**  
  Examined a dataset of tweets that include emojis, abbreviations, and embedded HTML tags. A significant class imbalance was observed, with "joy" dominating the labels.

- **Pre-processing:**  
  - Standardized sentences and converted emojis to words.
  - Applied spelling correction and abbreviation expansion.
  - Removed HTML tags and extra punctuation.
  - Extracted emotion-related features from hashtags and sentiment analysis libraries.

- **Feature Engineering:**  
  - Converted text into numerical features using TF-IDF.
  - Generated semantic embeddings with the paraphrase-mpnet-base-v2 model.
  - Reduced dimensionality using PCA and UMAP to retain essential information.

- **Model Experiments:**  
  Tested several models including Naive Bayes, Decision Tree, Random Forest, K-Nearest Neighbors, Neural Network, XGBoost, and DeBERTa.  
  DeBERTa performed best with a validation accuracy of 0.65 and a competitive Kaggle score.

For complete details—including data analysis, graphs, and further model insights—please refer to the attached PDF report.
