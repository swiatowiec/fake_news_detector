# FAKE NEWS DETECTOR
The aim of the task is to develop a classifier that, based on the content and title of the article, will assign one of four classes.

## ABOUT THE PROJECT
used official baseline: https://github.com/FakeNewsChallenge/fnc-1-baseline
Baseline model metrics: 8748.75 out of 11651.25  (75.0885098165433%)
LinearSVC (scikit-learn) was used for modeling
LinearSVC model metrics: 8898.0 out of 11651.25   (76.36948825233344%)

## DATA
https://github.com/FakeNewsChallenge/fnc-1

## HOW TO REPRODUCE
use req.txt file to install required packages.

## HOW TO IMPROVE
apply LSTM as linear SVC perform poorly
apply transformers (Bert, Roberta, ...) with Pytorch
the data are unbalanced, svc model needs some weights and hyperparameters tuning
apply model monitoring tool
refactor code (as one method should do one thing)
apply DVC for data versioning