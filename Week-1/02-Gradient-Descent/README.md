# Gradient Descent & Backpropagation

[Home](../../README.md) > [Week 1](../README.md) > Gradient Descent & Backpropagation

> Week 1 · Topic 2 of 4 · Prerequisites: [Introduction to ML](../01-Intro-to-ML/README.md)

---

## Why This Topic

If Topic 1 taught you *what* a neural network is, this topic teaches you *how* it learns. Every time a model makes a prediction, it measures how wrong it was (using a **loss function**), then adjusts its weights to be less wrong next time (using **gradient descent**). This loop - predict, measure error, adjust - is the heartbeat of all of modern machine learning, from simple linear regression to billion-parameter language models.

---

## What You Will Learn

- **Loss functions** - how we quantify "how wrong" a model's predictions are (MSE, cross-entropy, etc.)
- **Gradient Descent** - the optimization algorithm that minimizes the loss by iteratively updating weights in the direction of steepest decrease
- **Stochastic Gradient Descent (SGD)** - a computationally efficient variant that uses mini-batches instead of the full dataset
- **Backpropagation** - the algorithm that efficiently computes gradients by propagating error backward through each layer using the chain rule

---

## Why It Matters

Gradient descent is not just *one* technique - it is *the* technique. Nearly every model you will build in this course (and in industry) is trained using some variant of gradient descent. Understanding it deeply gives you:
- The ability to **debug training failures** (exploding/vanishing gradients, bad learning rates)
- Intuition for **hyperparameter tuning** (learning rate, batch size)
- A foundation for understanding **advanced optimizers** like Adam, RMSProp, and learning rate schedulers

Without this, model training is a black box. With it, you can reason about *why* your model is or isn't learning.

---

## Resources

**Watch:**
- [Gradient Descent, Step-by-Step - StatQuest](https://www.youtube.com/watch?v=sDv4f4s2SB8) - The intuition behind minimizing loss, explained clearly with examples
- [Stochastic Gradient Descent, Clearly Explained!!! - StatQuest](https://www.youtube.com/watch?v=vMh0zPT0tLI) - How to make gradient descent computationally efficient for large datasets
- [Gradient descent, how neural networks learn | Deep Learning Chapter 2 - 3Blue1Brown](https://www.youtube.com/watch?v=IHZwWFHWa-w) - Beautiful math and visuals behind network learning
- [Backpropagation, intuitively | Deep Learning Chapter 3 - 3Blue1Brown](https://www.youtube.com/watch?v=Ilg3gGewQ5U) - How error is pushed back through the network to update weights

---

## Deep Dive

If you have extra time or want a much deeper understanding of how backpropagation is implemented at the code level:

- [The spelled-out intro to neural networks and backpropagation: building micrograd - Andrej Karpathy](https://www.youtube.com/watch?v=VMj-3S1tku0) - Build a minimal autograd engine from scratch in Python, understanding exactly how gradients flow through a computation graph

- [An overview of gradient descent optimization algorithms - Sebastian Ruder](https://ruder.io/optimizing-gradient-descent/) - Comprehensive blog post covering SGD, momentum, Adam, and other optimizers you will encounter later

---

## Before You Move On

- Can you explain what a loss function does?
- Can you describe gradient descent in your own words (no equations needed)?
- Can you explain *why* we use mini-batches in SGD instead of the full dataset?
- Can you explain what backpropagation computes and why the chain rule is involved?

---

[Previous: Introduction to ML](../01-Intro-to-ML/README.md) | [Week 1 Overview](../README.md) | [Next: Programming Prerequisites](../03-Programming-Prerequisites/README.md)
