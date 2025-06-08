# 👗 Fashion MNIST Classifier (Fully-Connected Neural Network)

This project builds a Deep Learning model using **TensorFlow** to classify grayscale images of clothing from the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). The model is trained using a multi-layer perceptron (MLP) architecture and visualizes predictions, misclassifications, and training history.

---

## Dataset

Fashion MNIST is a dataset of 70,000 28×28 grayscale images of 10 clothing categories:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

---

## Model Architecture

```text
Input: 28×28 grayscale image → Flatten

Layer 1:
  - Dense(256) + ReLU activation
  - BatchNormalization
  - Dropout(0.3)

Layer 2:
  - Dense(128) + ReLU activation
  - BatchNormalization
  - Dropout(0.3)

Output:
  - Dense(10) + Softmax activation (for 10 classes)


