
# Handwritten Digit Recognition

## About the Project

This project uses a neural network built with TensorFlow and Keras to recognize handwritten digits from 0 to 9.

## Dataset

The project uses the MNIST dataset, which contains 70,000 grayscale images of handwritten digits.

- 60,000 training images
- 10,000 test images
- Image size: 28 × 28 pixels

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- pandas
- Matplotlib
- scikit-learn

## Project Structure

- `src/train.py` - Trains and evaluates the neural network.
- `src/predict.py` - Predicts a digit from a test image.
- `models/` - Stores the trained model.
- `outputs/` - Stores training graphs.
- `requirements.txt` - Lists Python package dependencies.

## How to Run

Install the required packages:

```bash
python -m pip install -r requirements.txt
```

Train the model:

```bash
python src/train.py
```

Run a prediction:

```bash
python src/predict.py
```

## Learning Goals

- Understand neural networks.
- Learn basic image preprocessing.
- Train and evaluate a machine learning model.
- Practice using Git and GitHub.
