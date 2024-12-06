# Qbias News Analysis

## Project Overview

This project explores bias in news articles using the Qbias dataset, a collection of 21,747 articles labeled with political bias categories (`Left`, `Center`, `Right`). The primary goal is to analyze patterns of bias, classify articles by bias, and generate summaries while retaining neutrality.

## Features

- **Dataset Analysis:** Explore and preprocess text data to identify bias trends.
- **Bias Classification:** Train machine learning and transformer models to classify articles by bias labels.
- **Summarization:** Experiment with extractive and abstractive summarization techniques.
- **Visualizations:** Present bias distributions, sentiment trends, and model performance.

## Dataset

- **Source:** 
[Preprocessed Article Data](https://drive.google.com/file/d/100WVVOQCeiVHxQqjK7mJxlKWbXUjdMt6/view?usp=sharing)
[Cleaned Suggestions Data](https://drive.google.com/file/d/100cGBVMDudcWRe2CPYUvtBkuX1HYS1gy/view?usp=sharing)

- **Details:** News articles labeled for political bias.

## Methodology

1. **Data Cleaning:** Preprocessing text (stopword removal, lemmatization, etc.).
2. **Exploratory Analysis:** Analyze sentiment, word frequency, and bias trends.
3. **Modeling:** Train classifiers and fine-tune transformers for bias detection.
4. **Summarization:** Use NLP techniques for article summarization.

## External Links and Resources

This notebook explored various models and techniques for classifying bias in news articles and integrating sentiment analysis into NLP tasks. The analysis was informed by the Hugging Face NLP course and leveraged datasets to train and evaluate models. Here's a summary of the key findings:

- **Hugging Face NLP Course:**  A full course on natural language processing. Chapter 1: Introduction to NLP, Section 3: Tokenization. [Link](https://huggingface.co/learn/nlp-course/chapter1/3)

**1. Baseline Model Performance:**

- Traditional machine learning models like Logistic Regression, Random Forest, SVM, Naive Bayes, k-NN, and Decision Tree were used as initial baselines for bias classification.
- These models achieved relatively modest accuracy scores, ranging from approximately 40% to 55%, indicating the complexity of the task.

#### 📈 Data

The following datasets were used in this analysis:

1. **AllSides Media Bias Ratings:**
    - **Source:** [AllSides Media Bias Ratings](https://www.allsides.com/media-bias/media-bias-ratings), [AllSides Scraper GitHub Repository](https://github.com/favstats/AllSidesScraper), Tools like AllSideR in R: [AllSideR GitHub](https://github.com/pablobarbera/AllSideR)
    - **Description:** AllSides provides bias ratings for over 2,400 media outlets, categorizing them as Left, Lean Left, Center, Lean Right, or Right. These ratings are determined through methods such as blind surveys, editorial reviews, and community feedback. 
2. **Qbias Dataset:**
    - **Source:** [Qbias on GitHub](https://github.com/Qbias/Qbias)
    - **Description:** The Qbias dataset comprises 21,747 news articles collected from AllSides' balanced news headline roundups as of November 2022. Each article is labeled with a political bias—Left, Center, or Right—based on expert annotations.
