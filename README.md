# Multinomial Logistic Regression Implementation

##  Overview
This project features a Python implementation of a **Multinomial Logistic Regression** model (Softmax Regression). It was developed to solve multi-class classification problems, extending the principles of binary logistic regression to handle multiple target categories.

##  Technical Implementation
Key components implemented in this project:
* **Softmax Activation:** Used in the output layer to provide a probability distribution across multiple classes.
* **Cross-Entropy Loss:** Implementation of the multi-class loss function to measure the model's performance.
* **One-Hot Encoding:** Logic for handling categorical target variables for multi-class labels.
* **Gradient Descent:** Optimization of weights and biases to ensure convergence across all class parameters.
* **Vectorization:** Efficient matrix math using **NumPy** for simultaneous weight updates.

##  Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** NumPy, Matplotlib.

##  Results
The notebook demonstrates the training process on a multi-class dataset (such as the full MNIST set with 10 digits), including a visualization of the loss curve.
