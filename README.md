

```markdown
#Homework 1
# MNIST Classification with PyTorch

This project demonstrates a simple implementation of a feedforward neural network (FNN) to classify handwritten digits from the MNIST dataset using PyTorch.

## Prerequisites

Before running this project, ensure you have the following installed on your system:
- Python (version 3.6 or later)
- PyTorch (version 1.8.0 or later)
- torchvision (version 0.9.0 or later)
- matplotlib

Or you can use the colab to run since everything is installed. Download the file and uploade on colab Link: https://github.com/singhamritanshu/CSE676/blob/main/Amritanshu_Singh_Homework1.ipynb
## Installation

1. **Python Dependencies**

   After cloning the project, navigate to the project directory and install the required Python packages using the following command:

   ```
   pip install torch torchvision matplotlib
   ```

2. **Dataset**

   The MNIST dataset will be automatically downloaded when you run the script for the first time.

## Usage

To run the MNIST classification script, execute the following command in your terminal:

```
python amritanshu_singh_homework1.py
```

This command will start the training process of the neural network on the MNIST dataset. After training, it will display a plot showing the training and test losses over the training iterations.

## Customizing Parameters

You can customize various training parameters directly in the `mnist_classification.py` script, such as:
- `epochs`: Number of training epochs.
- `batch_size`: Size of each training batch.
- `lr`: Learning rate for the optimizer.

```
