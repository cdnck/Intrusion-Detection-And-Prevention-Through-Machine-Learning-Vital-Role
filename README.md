# Intrusion Detection System using Machine Learning

This project is an Intrusion Detection System (IDS) built with Machine Learning to classify network traffic as normal or malicious.  
It uses a *Decision Tree Classifier* trained on the KDD dataset in a Kaggle notebook environment.

## Project Overview

Network security is an important concern in modern systems.  
This project applies machine learning to detect suspicious network behavior and support intrusion detection tasks.  
The model is trained on the KDD dataset, preprocessed with label encoding and numeric conversion, and evaluated using accuracy and classification metrics.

## Features

- Built in Kaggle Notebook environment.
- Uses the KDD dataset from Kaggle input files.
- Implements Decision Tree Classification for intrusion detection.
- Performs data preprocessing, label encoding, and train-test split.
- Saves the trained model as `idsdecisiontree.pkl`
- Saves the label encoder as `labelencoder.pkl`.
- Generates dataset visualization for class distribution.

## Dataset

The project uses the KDD intrusion detection dataset from Kaggle.  
The notebook automatically searches the Kaggle input directory and loads the CSV file from the dataset path.  
The dataset used in the notebook has a shape of `125973 x 42`.

## Model Used

- Algorithm: Decision Tree Classifie.
- Task: Binary/Multiclass intrusion classification.
- Evaluation Metric: Accuracy, classification report, confusion matrix.

## Results

The notebook reports a final test accuracy of 99.27%*.  
The model is saved after training for later use or deployment.

## Project Workflow

1. Load libraries.
2. Read the KDD dataset from Kaggle input.
3. Clean and preprocess the data.
4. Encode categorical features.
5. Split data into training and testing sets.
6. Train the Decision Tree model.
7. Evaluate performance.
8. Save the model and encoder [file:2].

## Files

- `ids-decision-tree.ipynb` — Kaggle notebook containing the full implementation.
- `idsdecisiontree.pkl` — trained Decision Tree model.
- `labelencoder.pkl` — saved label encoder.
- `classdistribution.png` — class distribution visualization.

## Requirements

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- pickle

## How to Run

1. Open the notebook in Kaggle.
2. Attach the KDD dataset to the notebook input.
3. Run all cells sequentially.
4. The trained model and encoder will be saved automatically.

## Author

Shifa Naaz
