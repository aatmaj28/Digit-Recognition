# ✏️ Handwritten Digits Recognition 🔢

![MNIST Dataset Sample](placeholder-for-mnist-image.png)

## 📝 Overview

This project implements a neural network model to recognize handwritten digits using the MNIST dataset. The model is built with TensorFlow and achieves high accuracy in classifying digits from 0-9.

## 🔍 Features

- 🧠 Neural network with multiple dense layers
- 📊 Training and evaluation on the MNIST dataset
- 💾 Model saving and loading capabilities
- 🖼️ Custom image prediction functionality
- 📉 Visualization of results using matplotlib

## 🛠️ Technologies Used

- Python
- TensorFlow
- NumPy
- OpenCV
- Matplotlib

## 🏗️ Model Architecture

The neural network consists of:
- Input layer (flattened 28×28 pixels)
- Two hidden layers with 128 neurons each and ReLU activation
- Output layer with 10 neurons and softmax activation

## 🚀 How to Use

1. Install the required dependencies:
```
pip install tensorflow opencv-python numpy matplotlib
```

2. Set `train_new_model = True` to train the model or `False` to use a pre-trained model.

3. Place your own handwritten digit images in the `digits/` folder with naming format `digit1.png`, `digit2.png`, etc.

4. Run the script:
```
python handwritten_digits_recognition.py
```

## 📋 Results

The model achieves approximately 97-98% accuracy on the MNIST test set after just 3 epochs of training.

## 🎓 Academic Context

This project was developed as part of the **IT3140 Soft Computing** course during my undergraduate studies at **Manipal University Jaipur**.

## 📊 Future Improvements

- Implement data augmentation for better generalization
- Try different model architectures (CNN, etc.)
- Create a web interface for real-time digit recognition
- Extend to recognize characters beyond digits

## 🔗 References

- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [TensorFlow Documentation](https://www.tensorflow.org/api_docs/python/tf)
