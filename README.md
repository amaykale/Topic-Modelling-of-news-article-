# Topic-Modelling-of-news-article-
This repository contains code and analysis for performing topic modelling on a dataset of news articles.

Overview
The project focuses on extracting meaningful topics from news article headings using Latent Dirichlet Allocation (LDA) technique. The dataset used consists of news articles categorized into 'business' and 'sports' types.

Requirements
Python 3.x
Libraries: pandas, nltk, gensim, pyLDAvis, wordcloud, matplotlib

Dataset
The dataset (Articles.csv) is stored in CSV format containing the following columns:

Article: Text content of the news article
Date: Publication date of the article
Heading: Headline of the article
NewsType: Categorical label ('business' or 'sports')

Usage
1. Data Loading and Preprocessing
Loading the Dataset: Load the dataset into a pandas DataFrame and inspect the first few rows.
2. Text Preprocessing
Tokenization and Cleaning: Tokenize the article headings, remove stopwords, and perform lemmatization using NLTK.
3. Topic Modelling
LDA Modelling: Train LDA models to discover topics within the news article headings. Visualize topics using pyLDAvis.
4. Visualization
Word Clouds: Generate word clouds for 'business' and 'sports' topics to visually represent frequent terms.

Time Series Plots: Plot daily and monthly article counts for 'business' and 'sports' news types.

5. Statistical Analysis
T-Test: Perform a statistical t-test to compare article counts between 'business' and 'sports' categories.
Results
The LDA modelling identified distinct topics within the news articles, revealing insights into prevalent themes across 'business' and 'sports' categories.

Contributing
Contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.
