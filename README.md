# Phishing Website Detection

## Overview

This project aims to develop a robust system for detecting phishing websites, which are malicious websites designed to steal sensitive information from users. Phishing attacks are a significant threat to cybersecurity, and detecting these websites accurately can help protect users from falling victim to such attacks.

## Features

The project includes the following features:

- **Feature Extraction**: Different kinds of features are extracted from URLs, web pages, domains, and HTML content to identify phishing websites. These features include URL-based features, page-based features, domain-based features, and HTML-based features.

- **Exploratory Data Analysis (EDA)**: The dataset is analyzed and visualized to understand its characteristics, patterns, and relationships. Various plots and metrics are used to explore the distribution of features and their correlations.

- **Machine Learning Algorithms**: Several machine learning algorithms are implemented and evaluated for phishing website detection, including:
  - Support Vector Machine (SVM)
  - Decision Trees and Random Forest
  - k Nearest Neighbors (KNN)

## Implementation Details

- **Feature Extraction**: Features are extracted manually from URLs and web pages, while some are obtained directly from the dataset. Various techniques are used to extract features such as domain registration length, presence of login forms, and URL length.

- **Machine Learning Models**:
  - Support Vector Machine (SVM): Different kernels and optimization algorithms are explored to train SVM models for classification.
  - Decision Trees and Random Forest: Variants of decision tree algorithms such as ID3, C4.5, and CART are implemented, along with ensemble methods like Random Forest.
  - k Nearest Neighbors (KNN): Different variants of the KNN algorithm are implemented, including Fuzzy KNN, Weight Adjusted KNN, Hassanat KNN, and Ensemble Approach KNN.

## Usage

Clone this repo using

    git clone https://github.com/mit-riya/Phishing-URL-Detection
Install dependencies

    pip install -r requirements.txt
    
Run the scripts for feature extraction, data analysis, and machine learning models as needed.

## Results

- The performance of each machine learning algorithm is evaluated using various metrics such as accuracy, precision, recall, and F1-score.
- Results are presented in tables and visualizations to compare the effectiveness of different algorithms and techniques.

## Contributors

- John Doe (@johndoe)
- Jane Smith (@janesmith)
