# 🧠 Handwritten Digit Recognition using Deep Learning

## 📌 Overview

This project implements a handwritten digit recognition system using deep learning techniques in Python. The model is trained on the MNIST dataset to classify digits (0–9) from grayscale images.

Handwritten digit recognition is widely used in real-world applications such as postal mail sorting, bank cheque processing, and form digitization.

---

## 🚀 Features

* Uses the MNIST dataset for training and testing
* Implements a neural network using TensorFlow/Keras
* Classifies digits from 0 to 9
* Supports prediction on custom handwritten digit images
* Model is saved and loaded for reuse

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib

---

## 📂 Project Structure

```
.
├── Digits/                # Custom input images (optional)
├── digitreco.keras       # Saved trained model
├── main.py               # Main script (training + prediction)
└── README.md             # Project documentation
```

---

## 📊 Dataset

The model is trained using the **MNIST dataset**, which consists of:

* 60,000 training images
* 10,000 testing images
* 28x28 grayscale images of handwritten digits (0–9)

---

## ⚙️ Model Architecture

The model is built using a simple feedforward neural network:

* Flatten layer (input: 28×28 images)
* Dense layer (128 neurons, ReLU activation)
* Output layer (10 neurons, Softmax activation)

---

## 🧪 Training

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 15

The model learns to map image pixel values to digit labels.

---

## 📈 Evaluation

The trained model is evaluated on test data to measure accuracy.
It achieves high accuracy on the MNIST dataset.

---

## 🔍 Prediction

The model can predict digits from custom images stored in the `Digits/` folder.

Steps:

1. Load image using OpenCV
2. Convert to grayscale
3. Preprocess image
4. Predict digit using trained model

---

## ⚠️ Limitations

* The model is trained on MNIST-style images, so performance may drop on real-world handwritten inputs.
* Custom images must be preprocessed properly (size, contrast, background).

---

## 📌 Future Improvements

* Use Convolutional Neural Networks (CNN) for better accuracy
* Implement data augmentation
* Build a GUI or web app for real-time digit recognition
* Improve preprocessing for real-world inputs

---

## ▶️ How to Run

1. Install dependencies:

```
pip install tensorflow opencv-python matplotlib numpy
```

2. Run the script:

```
python main.py
```

3. Add custom images in the `Digits/` folder for testing.

---

## 💡 Conclusion

This project demonstrates the implementation of a basic deep learning model for handwritten digit recognition. It provides a foundation for understanding image classification using neural networks.

---

## 👤 Author

* Ajvad

---
