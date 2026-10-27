# CNN for CIFAR-10

A simple convolutional neural network built with PyTorch to classify images from the CIFAR-10 dataset.

## What it does

- Downloads and normalizes CIFAR-10 automatically.
- Trains a CNN with three convolutional blocks and fully connected layers.
- Evaluates the trained model on the test set and prints accuracy.

## Requirements

- Python 3
- PyTorch
- Torchvision
- Jupyter Notebook

Install the dependencies with:

```bash
pip install torch torchvision jupyter
```

## Run

Open [CNN_for_CIFAR10.ipynb](CNN_for_CIFAR10.ipynb) in Jupyter Notebook or JupyterLab and run the cells in order:

```bash
jupyter notebook CNN_for_CIFAR10.ipynb
```

The CIFAR-10 dataset is downloaded into `./data` on the first run. Training uses 10 epochs and reports the test accuracy at the end.
