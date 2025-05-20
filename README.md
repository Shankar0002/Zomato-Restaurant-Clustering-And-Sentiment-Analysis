Zomato Restaurant Clustering & Sentiment Analysis
This project applies unsupervised machine learning and NLP techniques on Zomato restaurant data to solve two core business problems:

Clustering restaurants based on features like cuisine, pricing, and location to assist in market segmentation.

Sentiment analysis on user reviews to understand customer satisfaction trends and aid business strategy.

## Problem Statement
Zomato, a food delivery platform, needs insights into restaurant segmentation and customer sentiment to optimize its recommendations, marketing strategies, and partner onboarding. This project addresses both market clustering and user feedback analysis.

## Technologies & Tools Used
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, NLTK, WordCloud

Techniques: K-Means Clustering, TF-IDF Vectorization, Sentiment Classification

NLP: Text Preprocessing, Tokenization, Stopword Removal, Lemmatization

## Project Workflow
Data Cleaning & EDA

Handled missing values, filtered outliers

Visualized features like location distribution, price range, and ratings

Clustering Analysis (K-Means)

Selected features: average cost, rating, cuisine type, location

Applied elbow method for optimal cluster selection

Interpreted clusters to identify distinct market segments

Sentiment Analysis (NLP)

Preprocessed review text

Applied TF-IDF vectorization

Trained classification model to predict sentiment (positive/negative)

Visualized frequent words using WordCloud

## Key Outcomes
Segmented restaurants into meaningful clusters for marketing and product optimization

Identified customer sentiment patterns to inform service improvements

Built a foundational model for Zomato to enhance user experience using data-driven insights
