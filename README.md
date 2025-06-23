# 🧠 Deep Neural Network from Scratch – Cat Image Classifier (NumPy)

## 📌 Project Overview
This project implements a deep neural network from scratch using only **NumPy** to classify images of **cats vs non-cats**. The model is trained and evaluated on a binary image classification task, achieving:

- ✅ **98% training accuracy**
- ✅ **80% test accuracy**

It demonstrates a full forward and backward pass, weight initialization, manual backpropagation, and training using binary cross-entropy loss — all without using deep learning libraries.

---

## 🧠 Key Features

- Implemented multi-layer deep neural network (DNN) manually
- Vectorized forward propagation and backpropagation
- ReLU and Sigmoid activation functions
- Binary cross-entropy loss
- Gradient descent optimization

---

## 📊 Dataset Details

- Binary classification: **cat (1)** vs **non-cat (0)**
- Image size: 64x64 RGB
- Preprocessing: Flattened to 1D vectors of 12288 elements (64x64x3), normalized to [0, 1]
- Provided in `.h5` format

---

## 🧮 Model Architecture

| Layer | Type   | Units | Activation |
|-------|--------|-------|------------|
| Input | -      | 12288 | -          |
| 1     | Dense  | 20    | ReLU       |
| 2     | Dense  | 7     | ReLU       |
| 3     | Dense  | 5     | ReLU       |
| 4     | Dense  | 1     | Sigmoid    |

---

## 📈 Performance

| Metric       | Value  |
|--------------|--------|
| Train Accuracy | 98%   |
| Test Accuracy  | 80%   |

---

## 📸 Figures

- `figure1.png`: Cost vs Epoch  
- `figure2.png`: Accuracy Curve  
- `figure3.png`: Sample Predictions

---

## 📁 Files Included

- `Deep Learning App Part 1.ipynb`  
- `Deep Learning App Part 2.ipynb`  
- 5 figures to help demonstrate the architecture

---

## 🧠 Skills Demonstrated

- Forward/backward propagation from scratch
- Deep learning implementation without libraries
- Binary classification on real-world image data
- Vectorized matrix operations with NumPy

---

## 📎 References

- Dataset from Andrew Ng’s Deep Learning Specialization

---

## 👤 Author

** Muhammad Adam Umar**
