# German Credit Risk Prediction with PyTorch

## Project Overview

This project focuses on predicting credit risk using deep learning techniques implemented with PyTorch. We leverage the German Credit Risk Dataset, which contains various attributes representing the credit profiles of individuals. Our goal is to build a robust predictive model that can assess the creditworthiness of applicants.

### Dataset Description

- **Number of Datasets:** 1
- **Dataset Size:** 1000 entries
- **Number of Columns Used:** 15 after feature selection

## Data Processing

### Preprocessing
- Data preprocessing involves handling missing values and encoding categorical features using one-hot encoding and label encoding techniques.

### Feature Selection
- Feature selection is performed to identify relevant features for predicting credit risk.
- A threshold of 5% correlation with the target class is used to filter out low-correlation features.

## Modeling

### Model Architecture
- The deep learning model architecture consists of multiple fully connected layers with batch normalization and ReLU activation functions.

### Training
- The model is trained using binary cross-entropy loss and Adam optimizer.
- Training is performed over multiple epochs, iterating over batches of data.

## Results

The trained model achieves a test accuracy of approximately 73.50% in predicting credit risk based on the German Credit Risk Dataset.

