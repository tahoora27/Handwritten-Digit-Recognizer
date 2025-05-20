# Handwritten Digit Recognizer using CNN

This project uses a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset.

## 📊 Accuracy
Achieved **~98% accuracy** on the MNIST test set.

## 📁 Dataset
- Source: Keras built-in MNIST dataset
- 60,000 training images
- 10,000 test images

## 🧠 Model Architecture
- Conv2D + ReLU
- MaxPooling2D
- Conv2D + ReLU
- MaxPooling2D
- Conv2D + ReLU
- Flatten + Dense(64)
- Output layer: Dense(10, softmax)

## 🔧 Requirements
tensorflow
numpy
matplotlib
scikit-learn


## 🚀 How to Run
1. Clone this repo
2. Open `digit_recognizer.ipynb` in Jupyter or Colab
3. Run cells step by step



## 🎨 Unique Features
- Data augmentation (rotation, zoom)
- Confusion matrix
- Save/load model


