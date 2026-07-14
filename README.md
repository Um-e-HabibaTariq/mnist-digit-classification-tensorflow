# mnist-digit-classification-tensorflow
Digit classification on the MNIST dataset using TensorFlow/Keras with a comparative analysis of ReLU and Sigmoid activation functions.
# MNIST Digit Classification using TensorFlow

## Project Overview

This project implements a simple feed-forward neural network using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

Two different activation functions were evaluated:

- ReLU
- Sigmoid

The objective was to compare their performance in terms of:

- Training Accuracy
- Validation Accuracy
- Loss
- Convergence Speed

---

## Dataset

The project uses the built-in MNIST dataset provided by TensorFlow.

- 60,000 Training Images
- 10,000 Testing Images
- Image Size: 28 × 28 pixels
- Classes: 10 digits (0–9)

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## Data Preprocessing

- Pixel normalization (0–255 → 0–1)
- Flattened images (28×28 → 784)
- One-hot encoded labels

---

## Neural Network Architecture

Input Layer (784)

↓

Dense (128 neurons)

↓

Dense (64 neurons)

↓

Output Layer (10 neurons, Softmax)

---

## Activation Functions Compared

Model A

- ReLU

Model B

- Sigmoid

---

## Results

The ReLU model converged faster and achieved higher accuracy compared to the Sigmoid model.

---

## Project Structure

```text
README.md
mnist_digit_classification.ipynb
requirements.txt
images/
results/
```

---

## Future Improvements

- Add CNN implementation
- Hyperparameter tuning
- Confusion Matrix
- Precision and Recall
- TensorBoard Visualization

---

## Author

Um-e-Habiba Tariq
