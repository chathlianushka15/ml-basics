# 📐ML Basics - Learning Data Science 📐

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Learning-7ecba1?style=for-the-badge)

> Built while learning data science from scratch  every line of code understood, not just copied.

---

## What's Inside

Two complete beginner ML projects, covering the two fundamental types of machine learning problems.

---

## Project 1 - Iris Flower Classification

**Type:** Classification (predicting a category)

Given measurements of a flower (petal length, sepal width, etc.), predict which of 3 species it belongs to.

| Detail | Value |
|--------|-------|
| Dataset | Iris (150 flowers, built into scikit-learn) |
| Features | Sepal length, sepal width, petal length, petal width |
| Label | Species (Setosa, Versicolour, Virginica) |
| Model | Decision Tree Classifier |
| Training set | 120 flowers |
| Test set | 30 flowers |
| Accuracy | 100% |

**Key finding:** A single question - "Is petal length ≤ 2.45 cm?" - perfectly separates Setosa from the other two species.

---

## Project 2 - California House Price Prediction

**Type:** Regression (predicting a number)

Given details about a house and its neighborhood, predict its market price.

| Detail | Value |
|--------|-------|
| Dataset | California Housing (20,640 houses, built into scikit-learn) |
| Features | Income, house age, rooms, bedrooms, population, location |
| Label | House price (in $100,000s) |
| Model | Linear Regression |
| Training set | 16,512 houses |
| Test set | 4,128 houses |
| Mean Absolute Error | $53,320 |

**Key finding:** The model learned a genuine price trend but struggled with capped values ($500k ceiling in the dataset) and rare outlier houses with unusual feature combinations - both normal real-world data challenges.

---

## Concepts Learned

| Concept | What It Means                                                   |
|---------|-----------------------------------------------------------------|
| Features | Inputs the model uses to make a decision                        |
| Labels | The answer the model learns to predict                          |
| Classification | Predicting a category (flower species)                          |
| Regression | Predicting a number (house price)                               |
| Train/Test Split | 80% to learn from, 20% hidden to honestly test                  |
| `.fit()` | Training step - model studies patterns                          |
| `.predict()` | Model guesses on data it has never seen                         |
| Accuracy | For classification - % of correct guesses                       |
| MAE | For regression - average dollar amount the model was off by     |
| Decision Tree | A flowchart of yes/no questions the model learned               |
| Outliers | Unusual data points that confuse the model  normal in real data |

---
## Tech Stack

- Python 3.11
- scikit-learn
- pandas
- matplotlib
- Jupyter Notebook

---

## Author

**Anushka** - CSE Undergrad · Data Engineering & Environmental Informatics