
# CS6220 Data Mining

This repository contains my homework assignments for **CS6220 — Data Mining Techniques** at **Northeastern University**.

## Course

**Course:** CS6220 — Data Mining Techniques  
**University:** Northeastern University  
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

### Homework 4 — Association Rule Mining and Hierarchical Clustering

Implemented frequent itemset mining, association rule generation, and hierarchical agglomerative clustering algorithms.

**Topics covered:**
- Apriori frequent itemset mining
- Support calculation and frequent itemset discovery
- Candidate generation using JOIN
- Subset-based candidate pruning
- Support counting and pruning effectiveness
- Association rule generation using Apriori_rules
- Confidence-based rule pruning
- Support, confidence, and lift analysis
- Hierarchical agglomerative clustering (HAC)
- Single linkage (`min_dist`)
- Complete linkage (`max_dist`)
- Efficient incremental distance-matrix updates
- Dendrogram construction
- Cluster membership extraction and visualization
- Comparison of clustering outcomes

**Apriori and Association Rule Mining:**
- Transaction dataset: 20 transactions
- Minimum support: 0.25
- Minimum confidence: 0.60
- Frequent itemsets discovered: 10
- Qualifying association rules: 11
- Candidate pruning reduction at k = 3: 66.67%

**Hierarchical Clustering:**
- Dataset: `clustering.txt`
- Data points: 370
- Dimensions: 2
- Target clusters: 13
- Linkage methods: Single and Complete
- Full dendrogram: 369 merges

Single linkage better preserves elongated and curved structures, while complete linkage favors compact clusters.

**Main notebook:** [Homework 4 Jupyter Notebook](Homework-4/homework_4.ipynb)

**Dataset:** [clustering.txt](Homework-4/clustering.txt)

**Visualizations:**
- [Original Dataset Scatter Plot](Homework-4/Q9_dataset_scatter.png)
- [Single-Linkage Dendrogram](Homework-4/Q10_single_linkage_dendrogram.png)
- [Single-Linkage 13 Clusters](Homework-4/Q10_single_linkage_13_clusters.png)
- [Complete-Linkage Dendrogram](Homework-4/Ans11_complete_linkage_dendrogram.png)
- [Complete-Linkage 13 Clusters](Homework-4/Ans11_complete_linkage_13_clusters.png)

[View Homework 4](Homework-4/)

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
├── Homework-4/
│   ├── README.md
│   ├── homework_4.ipynb
│   ├── clustering.txt
│   ├── Q9_dataset_scatter.png
│   ├── Q10_single_linkage_dendrogram.png
│   ├── Q10_single_linkage_13_clusters.png
│   ├── Ans11_complete_linkage_dendrogram.png
│   ├── Ans11_complete_linkage_13_clusters.png
│   └── requirements.txt
│
├── .gitignore
└── README.md
```

## Running the Notebooks

Each homework directory contains its own README with assignment-specific information and execution instructions.

### 1. Clone the repository

```bash
git clone https://github.com/mihir1mathur/CS6220-Data-Mining.git
```

### 2. Navigate to the relevant homework directory

For example, for Homework 4:

```bash
cd CS6220-Data-Mining/Homework-4
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Execute the notebook

Open the relevant `.ipynb` file and run all cells sequentially.

For Homework 4, ensure `clustering.txt` is in the same directory as `homework_4.ipynb`.

## Technologies

- Python
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

## Notes

- Homework assignments are organized into separate directories.
- Each homework directory contains assignment-specific documentation.
- Python dependencies are specified in the corresponding `requirements.txt` files.
- Saved plots and visualizations are included where applicable.
- Homework 3 includes a ReLU training animation.
- Homework 4 includes Apriori mining results, association rule analysis, HAC dendrograms, and color-coded clustering visualizations.

## Key Learning Areas

- Classification and regression
- Model evaluation and hyperparameter analysis
- Neural networks and gradient-based learning
- Frequent itemset mining and association rules
- Hierarchical clustering and linkage methods
- Algorithm implementation and visualization
