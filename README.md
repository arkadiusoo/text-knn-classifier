# Text Document Classifier with k-NN

This project implements a Java-based application for classifying text documents using the k-Nearest Neighbors (k-NN) algorithm. The system processes the Reuters-21578 dataset and allows for feature-based classification with support for multiple distance metrics and similarity measures.

## Features

- **Feature Extraction Module**: Extracts at least 10 independent features from text documents, including both numerical and textual features.
- **k-NN Classifier Module**: Uses extracted features to classify documents based on configurable parameters such as:
  - Number of neighbors (k)
  - Train/test split ratio
  - Feature subset selection
  - Distance metric or similarity measure

## Supported Metrics

- Euclidean Distance
- Manhattan Distance
- Chebyshev Distance
- Custom similarity measures for textual features

## Evaluation

Classification results are evaluated using:
- Accuracy
- Precision (overall and per class)
- Recall (overall and per class)
- F1 Score

## Dataset

The project uses the Reuters-21578 Text Categorization Collection:
[UCI Dataset Link](http://archive.ics.uci.edu/dataset/137/reuters+21578+text+categorization+collection)

Only documents labeled with the following single 'places' categories are considered:
- west-germany
- usa
- france
- uk
- canada
- japan

## Additional Exploration

The project includes analysis of:
- Accuracy dependency on parameter **k**
- Accuracy based on train/test split ratio
- Metric/similarity influence on performance
- Feature importance by evaluating different subsets
