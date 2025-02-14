# Support Vector Machine (SVM) from Scratch

This repository contains an implementation of a Support Vector Machine (SVM) from scratch using NumPy and Matplotlib. The SVM is a powerful supervised learning algorithm used for classification tasks.

## Features

- Implements SVM without external machine learning libraries
- Supports binary classification
- Uses visualization to illustrate the decision boundary
- Utilizes the margin-maximizing approach for training

## Installation

Ensure you have Python installed along with the following dependencies:

```bash
pip install numpy matplotlib
```

## Usage

To use the SVM implementation, simply run the script and provide training data in the required format.

```python
from svm_scratch import supportVectorMachine

# Example data (features and labels)
data = {
    -1: np.array([[1,7], [2,8], [3,8]]),
     1: np.array([[5,1], [6,-1], [7,3]])
}

svm = supportVectorMachine()
svm.fit(data)
svm.visualize()
```

## Visualization

The script includes visualization capabilities to plot the decision boundary and support vectors.

## Contributing

Feel free to contribute by improving the implementation or adding new features.

## License

This project is licensed under the MIT License.
