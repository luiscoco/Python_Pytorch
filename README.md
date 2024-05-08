# Python a brief introduction to Pytorch

Getting started with PyTorch in VSCode is a great choice for diving into machine learning and deep learning with Python

Here are some simple steps and examples to help you begin your journey:

## 1. Install the Necessary Tools

Before you start coding, you need to have Python and VSCode installed on your computer

Additionally, you will need to install the PyTorch library. Here’s how you can do it:

**Install Python**: Download and install Python from python.org

**Install Visual Studio Code (VSCode)**: Download and install VSCode from code.visualstudio.com

**Install the Python extension for VSCode**: Open VSCode, go to the Extensions view by clicking on the square icon on the sidebar or pressing Ctrl+Shift+X, and search for the Python extension by Microsoft and install it

**Install PyTorch**: Open a terminal (or command prompt) and install PyTorch by running the following command:

```
pip install torch torchvision
```

## 2. Set Up a Simple PyTorch Project

Create a new folder for your project and open it in VSCode

Create a new Python file (e.g., simple_example.py)

Write your first PyTorch script. Below is a simple example that creates two tensors and multiplies them:

```python
import torch

# Create tensors.
x = torch.tensor([1, 2, 3])
y = torch.tensor([4, 5, 6])

# Perform tensor multiplication.
z = x * y

print(z)
```

Run your script by opening the terminal in VSCode (Terminal > New Terminal) and typing **python simple_example.py**

![image](https://github.com/luiscoco/Python_Pytorch/assets/32194879/71a73a00-97ac-4c3c-ab37-7480abb0122d)




