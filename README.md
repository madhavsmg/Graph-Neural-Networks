# Graph-Neural-Networks
This repository hosts implementations of various Graph Neural Networks (GNNs), including Graph Convolutional Networks (GCN), Graph Attention Networks (GAT), and GraphSAGE. These models are crucial in machine learning tasks involving graph-structured data, such as social network analysis, molecular chemistry, and recommendation systems.

# Graph Neural Networks Implementation

This repository contains implementations of various Graph Neural Networks (GNNs), including Graph Convolutional Networks (GCN), Graph Attention Networks (GAT), and GraphSAGE. The code is designed to run on Google Colab and uses the PyTorch Geometric library.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this notebook, you need to set up your environment with the required dependencies. Follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/graph-neural-networks.git](https://github.com/madhavsmg/Graph-Neural-Networks)
   cd graph-neural-networks


2. **Install Dependencies:**
   This notebook relies on PyTorch and PyTorch Geometric. Install the required packages using the following commands:
   ```bash
   pip install torch
   pip install torch-geometric
   pip install matplotlib networkx
   
3. **Run the Notebook:**
   Open the Project_K.ipynb file in Google Colab or Jupyter Notebook and run the cells sequentially.

## Usage
The notebook is structured to first explore and understand the implementation of different GNNs. It includes sections on:

1. **Exploring Graph Convolutional Networks:**
   Introduction and basics of GCNs.

2. **Implementing a GCN from Scratch:**
   Detailed steps and code to implement a GCN.

3. **Implementing Graph Attention Networks Using Citeseer Dataset:**
   Implementation details for GAT using the Citeseer dataset.

4. **GraphSAGE Implementation using Pubmed Dataset:**
   Instructions and code for implementing GraphSAGE.

5. **Mini-batching:**
   Explanation and implementation of mini-batching for training GNNs.

6. **Running the Models**
Each section of the notebook can be run independently. Follow the comments and instructions within each code cell to understand and execute the implementation.

## Code Structure
The main components of the notebook include:

1. **Accuracy Function and Training Loop:**
   Functions to calculate accuracy and the main training loop.
2. **Animation Setup:**
   Code to set up and visualize the training process.
3. **Training and Validation Loop:**
   Functions to train and validate the models.
4. **Test Function:**
   Function to evaluate the model on the test set.
5. **Model Implementations:**
   Code to implement and train GraphSAGE, GCN, and GAT models.

## Visualization
The notebook includes code to animate the training process, showing the changes in node embeddings, loss, and accuracy over epochs. The animation is generated using matplotlib.animation and can be viewed directly in the notebook.

## Contributing
If you wish to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure your code adheres to the existing style and includes relevant tests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
