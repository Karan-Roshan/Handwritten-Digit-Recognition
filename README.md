# Handwritten Digit Recognition
This project implements a **Handwritten Digit Recognition System** using **Deep Learning (TensorFlow/Keras)**.  
It is trained on the famous **MNIST dataset**, which contains 70,000 grayscale images of handwritten digits (0–9).

The model learns to recognize digits and can also predict digits from custom images stored locally.


## Features
- Trained on MNIST dataset
- Neural Network with Dense layers
- Predict custom handwritten digit images
- Displays prediction results visually
- Model saving and loading support


## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib


## Model Architecture
- Input Layer   →  784 nodes (28×28 flattened)
- Hidden Layer  →  128 nodes, ReLU activation
- Hidden Layer  →  128 nodes, ReLU activation
- Output Layer  →  10 nodes, Softmax activation (digits 0–9)


## Training Result
<p align="center">
  <img src="Project Results/Result1.png" width="400"/>
</p>

<p align="center">
  <img src="Project Results/Result2.png" width="400"/>
</p>

<p align="center">
  <img src="Project Results/Result3.png" width="400"/>
</p>

- Accuracy: ~97–98% (after 3 epochs)
- Loss: Low and stable


## Sample Output
```bash
The number is probably a 7
The number is probably a 3
The number is probably a 9
```