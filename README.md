# Data Visualization with Matplotlib

This repository contains Jupyter Notebooks focused on data visualization using the Matplotlib library. It focuses on charting model behavior, tracking performance over training steps, and auditing neural network model parameters.

## Featured Visualizations
* **Training History Curves:** Sequential tracking of model accuracy and loss across epochs to compare baseline models against L1 and L2 regularized variants.
* **Weight Distribution Histograms:** Auditing hidden layer weights to analyze how different regularization mechanics shift coefficient boundaries.

## Prerequisites & Installation
To run these notebooks and generate the plots locally, make sure you have the standard visualization and data analysis libraries installed:

```bash
pip install matplotlib numpy pandas seaborn
```

## How to Run
1. Clone this repository to your local machine.
2. Open the notebooks in Jupyter Notebook, JupyterLab, or VS Code.
3. Execute the cells to process the dataset configurations, run the model diagnostics, and generate the inline data plots.
