# MNIST Digit Classifier

A deep learning model built using **TensorFlow** inside a **Jupyter Notebook** to classify handwritten digits from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/). This project includes model building, training, prediction visualization, and accuracy/loss analysis.

---

## Highlights

- Uses the MNIST dataset of 70,000 handwritten digit images  
- Neural network with:
  - Dense layers
  - Batch Normalization
  - Dropout Regularization
- EarlyStopping to avoid overfitting
- Visualization of:
  - Predictions vs. True Labels
  - Accuracy and Loss over Epochs

---

## How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/mnist-digit-classifier.git
cd mnist-digit-classifier
```

2. Install Dependencies
```bash
pip install tensorflow matplotlib numpy

```

## Model Summary
- Input Layer:    Flatten 28x28
- Dense Layer:    256 units + ReLU
                BatchNormalization + Dropout(0.3)

- Dense Layer:    128 units + ReLU
                BatchNormalization + Dropout(0.3)

- Output Layer:   10 units (Softmax)

