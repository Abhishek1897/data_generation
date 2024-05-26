Introduction This repository contains two datasets, Dataset A and
Dataset B, along with Python scripts for data generation, preprocessing,
and classifier training and evaluation using scikit-learn.

Dataset A Description: Dataset A is a synthetic dataset generated using
make_classification from scikit-learn. It consists of 800 samples with
10 features and a binary target variable. File: data_A.csv Features:
feature_0 to feature_9 Target: target (binary) Preprocessing: Features
are standardized using StandardScaler, and the target variable is
encoded using LabelEncoder. Classifier Performance: Logistic Regression:
Average F1-score = 0.9504 Decision Tree: Average F1-score = 0.8948
Dataset B Description: Dataset B is a synthetic dataset generated using
make_classification from scikit-learn. It consists of 800 samples with
20 features and a binary target variable. File: data_B.csv Features:
feature_0 to feature_19 Target: target (binary) Preprocessing: Features
are standardized using StandardScaler, and the target variable is
encoded using LabelEncoder. Classifier Performance: Logistic Regression:
Average F1-score = 0.8045 Decision Tree: Average F1-score = 0.8315
Scripts Data Generation and Preprocessing:
data_generation_preprocessing.py: Python script for generating synthetic
datasets, preprocessing features, and saving data to CSV files.
Classifier Training and Evaluation: classifier_training_evaluation.py:
Python script for training Logistic Regression and Decision Tree
classifiers on the datasets and evaluating their performance using
cross-validation. Dependencies Python 3.x NumPy pandas scikit-learn
Usage Clone this repository. Run data_generation_preprocessing.py to
generate datasets and preprocess them. Run
classifier_training_evaluation.py to train classifiers and evaluate
their performance. Acknowledgments The synthetic datasets are generated
using scikit-learn\'s make_classification. Data preprocessing is done
using scikit-learn\'s StandardScaler and LabelEncoder. Classifier
training and evaluation are performed using scikit-learn\'s
LogisticRegression, DecisionTreeClassifier, and cross_val_score.
