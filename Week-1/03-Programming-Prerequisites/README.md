# Environment & Programming Prerequisites

[Home](../../README.md) > [Week 1](../README.md) > Programming Prerequisites

> Week 1 · Topic 3 of 4 · Prerequisites: [Gradient Descent & Backpropagation](../02-Gradient-Descent/README.md)

---

## Why This Topic

You now understand *what* ML does and *how* models learn. It is time to get your hands dirty. Machine Learning is a code-heavy field - Python is its lingua franca, and libraries like NumPy, Pandas, and Matplotlib are the tools you will use in virtually every project. This section gets you set up and fluent in the data science toolkit so that from Week 2 onward, you can focus on ML concepts instead of fighting with tools.

---

## What You Will Learn

- **Google Colab** - a free, browser-based Jupyter notebook environment with GPU access, so you can run ML code without any local setup
- **Python fundamentals** - variables, loops, functions, list comprehensions, and other essentials for writing clean ML code
- **NumPy** - the foundation of numerical computing in Python: arrays, vectorized operations, broadcasting, and linear algebra
- **Matplotlib** - creating plots and visualizations to understand your data and debug your models
- **Pandas** - loading, cleaning, filtering, and transforming tabular data (CSVs, DataFrames)

---

## Why It Matters

These are not optional extras - they are **the** tools of the trade. Every ML paper, Kaggle competition, and production pipeline uses them:
- **NumPy** is the backbone of nearly every ML library (PyTorch, TensorFlow, scikit-learn all build on it)
- **Pandas** is how you load, explore, and prepare real-world datasets
- **Matplotlib** is how you visualize training curves, data distributions, and model outputs
- **Google Colab** removes hardware barriers - you get free GPUs for training models

Investing time here pays dividends for the rest of the course and beyond.

---

## Resources

**Environment Setup:**
- [Welcome to Colaboratory - Google](https://colab.research.google.com/notebooks/intro.ipynb#scrollTo=5fCEDCU_qrC0) - Learn how to run Python code in the browser using Jupyter-style notebooks

**Python Basics:**
- [Kaggle Learn: Python](https://www.kaggle.com/learn/python) - Interactive course covering everything from syntax to functions

**Data Science Libraries (The "Holy Trinity"):**
- **NumPy** (Math & Arrays): [NumPy: the absolute basics for beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
- **Pandas** (Data Manipulation): [Kaggle Learn: Pandas](https://www.kaggle.com/learn/pandas)
- **Matplotlib** (Plotting/Visuals): [Matplotlib: Pyplot Tutorial](https://matplotlib.org/stable/tutorials/pyplot.html)

> **Tip:** It is recommended to practice these yourself in a Colab notebook. Reading documentation passively is not enough - type the code, modify it, and break it to build real fluency.

---

## Deep Dive

If you have extra time or want a much deeper understanding of the library mechanics, these detailed chapters by Pandas creator Wes McKinney are excellent:

- [Python for Data Analysis: NumPy Basics](https://wesmckinney.com/book/numpy-basics) - In-depth coverage of array internals, advanced indexing, and broadcasting rules
- [Python for Data Analysis: Pandas Basics](https://wesmckinney.com/book/pandas-basics) - Comprehensive guide to Series, DataFrames, and data alignment

---

## Before You Move On

- Can you create a new Google Colab notebook and run a Python cell?
- Can you create a NumPy array, reshape it, and perform element-wise operations?
- Can you load a CSV file into a Pandas DataFrame and filter rows based on a condition?
- Can you create a basic line plot and bar chart with Matplotlib?

---

[Previous: Gradient Descent](../02-Gradient-Descent/README.md) | [Week 1 Overview](../README.md) | [Next: Data Pre-processing & NLP](../04-Data-Preprocessing-NLP/README.md)
