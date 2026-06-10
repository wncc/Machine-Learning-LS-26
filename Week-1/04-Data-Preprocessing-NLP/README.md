# Data Pre-processing & Introduction to NLP

[Home](../../README.md) > [Week 1](../README.md) > Data Pre-processing & NLP

> Week 1 · Topic 4 of 4 · Prerequisites: [Environment & Programming Prerequisites](../03-Programming-Prerequisites/README.md)

---

## Why This Topic

Real-world data is messy, incomplete, and rarely in a format that ML models can consume directly. This section teaches you the critical bridge between "raw data" and "model-ready data." You will also get your first exposure to Natural Language Processing (NLP) - the branch of ML that deals with human language - and learn about tokenization, the process that converts text into numbers so models can understand it.

---

## What You Will Learn

- **Data splits** - why we divide data into Training, Validation, and Test sets, and what goes wrong if you don't
- **Basic text cleaning** - removing noise, handling missing values, normalization techniques
- **Introduction to NLP** - what NLP is, why text is harder than tabular data, and the key challenges
- **Tokenization** - how text is broken down into tokens (words, subwords, or characters) and converted into numerical representations that models can process

---

## Why It Matters

**"Garbage in, garbage out"** is the oldest rule in data science, and it is completely true. No model - no matter how sophisticated - can learn good patterns from bad data. Data preprocessing is often 60–80% of the work in real ML projects.

Tokenization, specifically, is the **entry point to all modern NLP**. Every model from BERT to GPT starts by tokenizing text. Understanding this process early gives you a huge head start when we dive deeper into NLP and transformer architectures in later weeks.

---

## Resources

**General Data Preprocessing:**
- [Kaggle Learn: Data Cleaning](https://www.kaggle.com/learn/data-cleaning) - Interactive course on handling missing values, inconsistent data, and character encodings

**Intro to NLP:**
- [Introduction to NLP](https://youtu.be/fLvJ8VdHLA0?si=3J-O1uQLccL0dg4I) - High-level overview of what NLP is and why it matters

**Practical Text Processing & Splits:**
- [Kaggle Code: Getting Started with NLP for Absolute Beginners](https://www.kaggle.com/code/jhoward/getting-started-with-nlp-for-absolute-beginners) - Hands-on guide by Jeremy Howard covering basic text processing and creating training/validation splits

**Tokenization Theory:**
- [Let's build the GPT Tokenizer - Andrej Karpathy](https://www.youtube.com/watch?v=zduSFxRajkE) **(Only up to 27:02)** - Deep dive into how tokenizers work under the hood (BPE algorithm, encoding/decoding)

---

## Before You Move On

- Can you explain why we split data into train/validation/test sets?
- Can you describe what "data leakage" is and why it is dangerous?
- Can you explain what tokenization does and why we need it?
- Can you describe the difference between word-level and subword tokenization?

---

[Previous: Programming Prerequisites](../03-Programming-Prerequisites/README.md) | [Week 1 Overview](../README.md)
