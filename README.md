# Feature-Engineering
Feature engineering is a machine learning technique that leverages data to create new variables that aren’t in the training set.
It can produce new features for both supervised and unsupervised learning, with the goal of simplifying and speeding up data transformations while also enhancing model accuracy.
Feature engineering is required when working with machine learning models. Regardless of the data or architecture, a terrible feature will have a direct impact on your model.

You can refer [towardsdatascience](https://towardsdatascience.com/what-is-feature-engineering-importance-tools-and-techniques-for-machine-learning-2080b0269f10) article for detailed description.

Note-
Refer kaggle for missing datasets
Eg- for [creditcard dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud?select=creditcard.csv)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install scikit-learn
```

```bash
pip install pandas
```

```bash
pip install numpy
```

```bash
pip install matplotlib
```

## Usage

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

#reads the given csv file
csvData = pd.read_csv("xyz.csv")

#generates an array of given parameters 
a = np.arange(15).reshape(3, 5)



```
