# Autoencoder for Supervised Classification
Comparison of MNIST classification with/without autoencoder using Logistic Regression, Linear SVM, Random Forest, and Neural Network. In this experiment the output from encoder is used as input to the classification algorithm.

# Results - Accuracy Score
|Data	|Logistic Regression	|Linear SVM	|Random Forest	|Neural Network|
| ------------- | ------------- | ------------- | ------------- | ------------- |
|Original	|0.9201	|0.9183	|0.9471	|0.9832|
|Encoded	|0.8746	|0.8804	|0.9182	|0.9799|


## Prerequisites
```
- Python 2
- Keras
- matplotlib
- numpy
- tensorflow
```

#### References:
- https://blog.keras.io/building-autoencoders-in-keras.html

