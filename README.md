# Fashion Article Classification (Fashion MNIST)

This is the code for a fashion article classifier that detects clothing and accessories, from the [Zalando Research Fashion MNIST repository](https://github.com/zalandoresearch/fashion-mnist).

## Overview

I built a 3-layer feedforward neural network which classifies different clothing / accessory items such as t-shirts, trousers, dresses, sneakers, and bags using the [TensorFlow](https://www.tensorflow.org/) library. The inputs are black and white images of size 28x28, and the output is an integer (corresponding to the target class).

The model was able to classify the test set with an accuracy of **~89.6%**.

## Dependencies

- numpy
- tensorflow

Install dependencies using [pip](https://pip.pypa.io/en/stable/).

## Dataset

The data set was taken from the [Fashion MNIST repository](https://github.com/zalandoresearch/fashion-mnist) by [zalandoresearch](https://github.com/zalandoresearch). The training set contains 60,000 examples and the test set contains 10,000 examples. Each example is a 28x28 grayscale image, and has an associated label from 10 classes.

| Class label  | Definition |
| ------------- | ------------- |
| 0  | T-shirt/top  |
| 1  | Trouser  |
| 2  | Pullover  |
| 3  | Dress  |
| 4  | Coat  |
| 5  | Sandal  |
| 6  | Shirt  |
| 7  | Sneaker  |
| 8  | Bag  |
| 9  | Ankle boot  |

## Usage

Run the notebook on a localhost server using `jupyter notebook`.
