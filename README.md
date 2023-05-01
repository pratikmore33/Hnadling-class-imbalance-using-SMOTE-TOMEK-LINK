# Hnadling-class-imbalance-using-SMOTE-TOMEK-LINK
handling class imbalance using smote

README for Handling Class Imbalance using SMOTE-TOMEK LINK

This is a repository for the implementation of SMOTE-TOMEK LINK algorithm for handling class imbalance in machine learning tasks. The algorithm combines the synthetic oversampling technique SMOTE (Synthetic Minority Over-sampling Technique) with the undersampling technique TOMEK LINK (Tomek Links) to remove the noisy and borderline samples from the majority class.

The repository contains the following files:

1. `smote_tomek_link.py`: This file contains the implementation of the SMOTE-TOMEK LINK algorithm.

2. `README.md`: This file contains the information about the repository.

3. `requirements.txt`: This file contains the required dependencies for running the code.

## Dependencies

The code is written in Python 3.8 and requires the following dependencies:

- numpy
- pandas
- imbalanced-learn


```

## Usage

To use the SMOTE-TOMEK LINK algorithm, you can import the `smote_tomek_link` module in your Python script:

```python
import smote_tomek_link as stl
```

The module provides a single function:

```python
stl.smote_tomek_link(X, y)
```

where `X` is the input feature matrix and `y` is the target variable.

## Example

You can find an example of how to use the SMOTE-TOMEK LINK algorithm in the `example.ipynb` Jupyter Notebook in this repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
