# Machine Learning for Physics — LCP Module B Exercises

Solutions to the exercises of the **Laboratory of Computational Physics – Module B** course (MSc in Physics of Data, University of Padova, A.Y. 2025/26).

The exercises cover the main tools of supervised and unsupervised machine learning applied to synthetic physics-like datasets: dense and convolutional neural networks, hyperparameter search, regularization, gradient boosting and clustering. All notebooks are written in Python with **Keras/TensorFlow**, **scikit-learn** and **XGBoost**.

Group 2609: Marco Lorenzato, Kevin Brugnera, Nicolò Teneggi, Polina Gridiaeva.

## Contents

| Folder | Topic | What was done |
|---|---|---|
| `Ex1` | Deep Neural Networks | Hyperparameter random search with `keras_tuner`, K-fold cross-validation, effect of data reduction and data augmentation |
| `Ex2` | Convolutional Neural Networks | 1D CNN for time-series classification; performance vs. signal amplitude; L1/L2 regularization and choice of λ by cross-validation |
| `Ex3` | XGBoost | Tuning of λ, γ, learning rate and number of estimators; feature selection; comparison with a feed-forward NN for different training-set sizes |
| `Ex4` | Clustering | DBSCAN parameter scan with NMI heat-maps, PCA visualization of 12-dimensional data, comparison with k-means |

## Repository structure

```
├── Ex1/
│   ├── group2609_exercise1.ipynb
│   ├── useful.py              # helper functions used by the notebook
│   └── DATA/
├── Ex2/
│   ├── group2609_exercise2.ipynb
│   └── DATA/
├── Ex3/
│   ├── group2609_exercise3.ipynb
│   ├── img.png
│   └── DATA/
├── Ex4/
│   ├── group2609_exercise4.ipynb
│   ├── img.png
│   └── DATA/
└── README.md
```

## Requirements

Python 3 with `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn`, `tensorflow`/`keras`, `keras_tuner`, `xgboost`.

Each notebook reads its data from the `DATA/` folder next to it.
