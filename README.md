# Article Narratives

This project focuses on assigning various narratives and sub-narratives to articles.

# Project Description & Objective

There are 20 narratives and 84 sub-narratives. The primary goal is to train a model to assign one or more sub-narratives to 50 test articles, using 400 training articles, although narrative predictions are also required. These articles typically focus on topics like climate change, international politics, and war, each containing approximately 500 words.

# Methodology

The project begins with BERT variants to create word embeddings and then explores classical machine learning approaches. Optuna is used to optimise the models, along with additional features generated through summarisation techniques using decoders like Llama and GPT. Semantic analysis, including VADER and TextBlob, is applied to capture subjectivity and sentiment (e.g., positivity) as further features to enhance model performance.

# Results

Using these methods, the model achieved an F1 Score (Macro) of 0.282.
