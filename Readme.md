# Named Entity Tagger using Flair Embeddings for V_mock Company

This repository contains the code and resources to train a Named Entity Tagger utilizing the power of Flair Embeddings. The model is trained on the `conllpp_train` dataset and tested on the `conllpp_test` dataset.

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Dataset](#dataset)
4. [Flair Embeddings](#flair-embeddings)
5. [Training the Model](#training-the-model)
6. [Testing the Model](#testing-the-model)
7. [Results](#results)
8. [Contributors](#contributors)
9. [License](#license)

## Introduction

Named Entity Recognition (NER) is an integral component of information extraction. By leveraging Flair Embeddings, we aim to improve the identification and classification of named entities in text for the V_mock company.

## Requirements

- Python 3.8+
- Libraries:
  - flair
  - scikit-learn
  - pandas
  - numpy

To install the requirements, use:

```bash
pip install -r requirements.txt
```

## Dataset

The conllpp_train dataset is used for training, and the conllpp_test dataset for evaluation.

## Flair Embeddings

Flair embeddings are contextual string embeddings for NLP, which have shown to provide significant improvements across various tasks. We'll utilize these embeddings to enhance the performance of our NER model.

## Training the Model

Steps to train the model:

1. Load the conllpp_train dataset.
2. Preprocess the data.
3. Set up the Flair Embeddings.
4. Define the model architecture with Flair Embeddings integration.5. 
6. Train the model on the dataset.
7. Save the model for subsequent use.

## Testing the Model
After training, evaluate the model's performance on the conllpp_test dataset

## Results
Post-testing, the results, encompassing metrics like accuracy, precision, recall, and F1-score, will be stored in the results.txt file.

Contributors

- [Ktk25](https://github.com/Ktk25)

## License
This project is under the MIT License. Refer to LICENSE.md for more details.
