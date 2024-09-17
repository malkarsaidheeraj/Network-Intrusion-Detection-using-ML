# Network-Intrusion-Detection-using-ML

## Project Overview
This project focuses on analyzing network traffic data to develop a Network Intrusion Detection System (NIDS). We use machine learning techniques to classify network connections as normal or various types of attacks.

## Dataset
The dataset used in this project is a modified version of the KDD Cup 1999 dataset, containing network connection data with various features and labels indicating the type of connection (normal or specific attack types).

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering and selection
- Dimensionality reduction using PCA
- Visualization techniques including t-SNE
- Implementation and comparison of multiple machine learning models

## Models Implemented
1. Random Forest Classifier
2. Support Vector Machine (SVM)
3. K-Nearest Neighbors (KNN)
4. Multinomial Logistic Regression

## Key Findings
- KNN model performed the best among the implemented models, achieving an accuracy of 97.72% on the validation set.
- Feature importance analysis revealed key indicators for network intrusions.
- PCA was effective in reducing dimensionality while maintaining most of the variance in the data.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly

## Usage
1. Clone the repository
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python script to reproduce the analysis

## Future Work
- Implement deep learning models for comparison
- Explore real-time intrusion detection capabilities
- Investigate the performance on more recent network intrusion datasets
