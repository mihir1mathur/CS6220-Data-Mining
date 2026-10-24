# CS6220 Data Mining

This repository contains my homework assignments for **CS6220 — Data Mining Techniques** at Northeastern University.

## Course

**Course:** CS6220 — Data Mining Techniques  
**Student:** Mihir Mathur

## Homework Assignments

### Homework 1 — Logistic Regression

Implemented and evaluated a Logistic Regression classification model using the Iris dataset.

**Topics covered:**
- Data loading and visualization
- Train/test splitting
- Feature standardization
- Logistic Regression
- Prediction accuracy
- Runtime measurements
- Hyperparameter experiments
- Confusion matrix evaluation

[View Homework 1](Homework-1/)

### Homework 2 — Linear Regression and Regression Trees

Implemented and evaluated linear regression and regression tree algorithms using synthetic datasets, with experiments comparing prediction accuracy, model complexity, and overfitting.

**Topics covered:**
- Linear regression using the Normal Equation
- Polynomial regression
- Training and testing RMSE
- Regression tree implementation
- Tree complexity and stopping conditions
- Model comparison
- Overfitting and the bias-variance tradeoff
- Hyperparameter analysis

[View Homework 2](Homework-2/)

### Homework 3 — Perceptrons and Neural Networks

Implemented and analyzed machine learning models and neural network training methods, including perceptrons, activation functions, loss functions, and gradient flow.

**Topics covered:**
- k-nearest neighbors (k-NN)
- Perceptron implementation and training
- Neuron learning and gradient descent
- ReLU, sigmoid, and tanh activation functions
- Squared error and absolute error
- Learning rate experiments
- ReLU training animation
- Multilayer neural networks
- MNIST classification experiments
- Gradient flow analysis across neural network layers
- Mean squared error and cross-entropy loss

**Main notebook:** [Homework 3 Jupyter Notebook](Homework-3/homework_3_002535005.ipynb)

**Additional notebook:** [MNIST Gradient Flow Experiments](Homework-3/HW3-gradient_flow_mnist.ipynb)

**Animation:** [ReLU Neuron Training GIF](Homework-3/Q9_ReLU_Training.gif)

[View Homework 3](Homework-3/)

## Repository Structure

```text
CS6220-Data-Mining/
│
├── Homework-1/
│   ├── README.md
│   ├── homework_1.ipynb
│   ├── iris.data
│   ├── iris.names
│   └── requirements.txt
│
├── Homework-2/
│   ├── README.md
│   ├── homework_2.ipynb
│   └── requirements.txt
│
├── Homework-3/
│   ├── README.md
│   ├── homework_3_002535005.ipynb
│   ├── HW3-gradient_flow_mnist.ipynb
│   ├── Q9_ReLU_Training.gif
│   └── requirements.txt
│
├── .gitignore
└── README.md
```

## Running the Notebooks

Each homework directory contains its own README with assignment-specific information and execution instructions.

To run a homework notebook:

1. Clone this repository:

   ```bash
   git clone https://github.com/mihir1mathur/CS6220-Data-Mining.git
   ```

2. Navigate to the relevant homework directory, for example:

   ```bash
   cd CS6220-Data-Mining/Homework-3
   ```

3. Install the required dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the relevant notebook and execute its cells in order.

## Notes

- Homework assignments are organized into separate directories.
- Each homework directory contains its own documentation and dependencies.
- Saved plots and visualizations are included where applicable.
- Interactive animations may require running the notebook locally; Homework 3 also provides a GIF for GitHub viewing.
