# Opinion Mining and Linguistic Analysis for Market Insights

This repository contains the source code and documentation for the Manning liveProject titled "Opinion Mining and Linguistic Analysis for Market Insights". This project involves applying Natural Language Processing (NLP) techniques to analyze customer reviews and gain insights into the video game market.

## Project Overview

As an NLP Specialist on the Growth Optimization Team of a startup launching a new video game, your role is to extract meaningful insights from customer reviews. This involves determining the sentiment of reviews, comparing sentiment scores with review ratings, and identifying key aspects that make a video game appealing or unappealing to gamers.

## Key Tasks

- **Dataset Preparation:** Download and create a custom dataset from Amazon video game reviews.
- **Sentiment Analysis:** Implement sentiment analysis using both dictionary-based methods and neural network-based models (DistilBERT).
- **Evaluation:** Assess the performance of sentiment analysis methods using scikit-learn.
- **Visualization:** Use Altair to visualize preferred and non-preferred aspects of video games based on customer reviews.

## Techniques and Tools

- **Data Sampling:** Imbalanced dataset handling with imbalanced-learn.
- **Sentiment Analysis:** NLTK for dictionary-based analysis, Pytorch, and transformers for deep learning models.
- **Model Evaluation:** scikit-learn for performance metrics and descriptive statistics.
- **Visualization:** Altair for data visualization.

## Project Structure

1. **Dataset Creation:** Preparing the Amazon review dataset.
2. **Dictionary-Based Sentiment Analyzer:** Implementing and evaluating a basic sentiment analysis tool.
3. **Neural Network-Based Sentiment Analyzer:** Building and assessing advanced sentiment analysis models using DistilBERT.
4. **Results Reporting:** Summarizing findings and presenting insights to the Growth Optimization Team.

## Dataset

The Amazon review dataset for video games can be downloaded from [here](https://nijianmo.github.io/amazon/index.html). Use the "video games 5 core" category under "Small subsets for experimentation".

## Repository Structure

- **data/**: Contains the dataset and any preprocessing scripts.
- **notebooks/**: Jupyter notebooks with code and analysis.
- **models/**: Scripts for building and evaluating sentiment analysis models.
- **visualization/**: Code for visualizing the results using Altair.
- **reports/**: Summary reports and findings.

This project simulates real-world tasks you might encounter as an NLP Specialist, providing hands-on experience with advanced data analysis and machine learning techniques in the context of market research.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## .gitignore

A `.gitignore` file is included to exclude common Python files and directories that shouldn't be committed to the repository, such as virtual environments, compiled files, and cache directories.
