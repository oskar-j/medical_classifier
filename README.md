# Medical classifier

Full stack machine learning - a scikit model in action

# Introduction 

# Description

## Data

## Exploratory analysis



## Solution (model)

In short:
1. It's possible to build a model which predicts health with 0.965667 recall and 0.973480 F-1 score
2. Best algorithm of machine learning is the Multi-layer Perceptron classifier
3. It's possible to hyper tune it and get only 0.1% better F-1 score
4. Model is robust, which was proved by cross validation and running on a bigger test sample
5. Dataset needs some feature engineering though
6. We may play around more with dimensionality reduction by using methods alternative to PCA
7. It's not obvious which score function to choose, although a harmonic sum of precision and recall should be enough
8. There may be a slight risk of over-fitting, but I'd need more of your data to verify this