# Fashion MNIST CNN From Scratch

## Project Title

UE24CS645BC2_PES1PG25CS045_Fashion_MNIST_CNN

---

## Project Description

This project implements a Convolutional Neural Network (CNN) completely from scratch using Python and NumPy without using deep learning frameworks such as PyTorch or TensorFlow for model building.

The CNN model is trained and evaluated on the Fashion MNIST dataset, which contains grayscale images of clothing items belonging to 10 different classes.

The project demonstrates the implementation of:

* Convolution operation
* Convolution layer
* Forward propagation
* Backpropagation
* Max Pooling layer
* Fully Connected layer
* Activation functions
* CNN training pipeline
* Model evaluation

---

## Dataset

The Fashion MNIST dataset contains:

* 70,000 grayscale images
* Image size: 28 × 28 pixels
* 10 fashion categories

Classes:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

Dataset Source:
Fashion MNIST Dataset from Keras/TensorFlow

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* TensorFlow/Keras (only for loading dataset)
* Google Colab

---

## CNN Architecture

The implemented CNN architecture consists of:

1. Convolution Layer
2. ReLU Activation Function
3. Max Pooling Layer
4. Fully Connected Layer
5. Softmax Output Layer

---

## Implemented Components

### 1. Convolution Layer

* Performs feature extraction using filters/kernels
* Applies convolution operation on input image

### 2. Forward Pass

* Propagates input through CNN layers
* Produces output probabilities

### 3. Backward Pass

* Performs backpropagation
* Updates weights using gradients

### 4. Max Pooling Layer

* Reduces spatial dimensions
* Extracts dominant features

### 5. Fully Connected Layer

* Converts extracted features into classification outputs

### 6. Activation Functions

* ReLU activation
* Softmax activation

### 7. Training Function

* Performs:

  * Forward propagation
  * Loss calculation
  * Backpropagation
  * Weight updates

### 8. Model Evaluation

* Calculates:

  * Test Loss
  * Test Accuracy

---

## How to Run the Project

### Step 1

Open Google Colab.

### Step 2

Upload the notebook/code file.

### Step 3

Run all cells sequentially.

---

## Sample Output

The model outputs:

* Training Loss
* Training Accuracy
* Test Loss
* Test Accuracy
* Sample Predictions

---

## Project Structure

```text
UE24CS645BC2_PES1PG25CS045_Fashion_MNIST_CNN/
│
├── README.md
├── Fashion_MNIST_CNN_From_Scratch.ipynb
└── output_images/
```

---

## Author

Name: Niveditha Amarnath

USN: PES1PG25CS045

Course: Deep Learning Techniques and Practice

---

## Conclusion

This project demonstrates the complete implementation of a CNN from basic principles using only Python and NumPy. The project helped in understanding the internal working of convolutional neural networks including convolution, pooling, activation functions, backpropagation, and model training.
