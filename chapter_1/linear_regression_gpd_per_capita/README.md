# Life Satisfaction vs. GDP per Capita

A small project from my studies of **Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (3rd edition)** by Aurélien Géron.

**Chapter studied:** Chapter 1 – The Machine Learning Landscape

## What I did

- Loaded the `lifesat` dataset from the book's data repository ([ageron/data](https://github.com/ageron/data)).
- Plotted GDP per capita against life satisfaction in a scatter plot.
- Trained a **Linear Regression** model (model-based learning).
- Predicted the life satisfaction for Cyprus (GDP per capita of 37,655.2 USD).
- Compared it with **k-Nearest Neighbors** (instance-based learning).

## What I learned

- The difference between model-based and instance-based learning.
- Scikit-Learn expects `X` as a 2D array (rows and columns), so I used `lifesat[["GDP per capita (USD)"]]`.
- How to read the model results: `coef_` and `intercept_`.

## Tools

Python, pandas, NumPy, Matplotlib, Scikit-Learn, Jupyter Notebook

## How to run

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
jupyter notebook
```

Then open the notebook and run all cells.