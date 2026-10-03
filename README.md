# Decision Tree - Classification

## 📌 Project Overview

This project demonstrates the implementation of a **Decision Tree Classifier**, a supervised machine learning algorithm used for classification problems.

A Decision Tree makes predictions by splitting the dataset into smaller groups based on feature values. It creates a tree-like structure consisting of decision nodes, branches, and leaf nodes.

---

## 🎯 Objective

The main objectives of this project are:

- Understand the Decision Tree algorithm
- Perform data preprocessing and cleaning
- Split the dataset into training and testing sets
- Build a Decision Tree Classification model
- Make predictions using the trained model
- Evaluate model performance using classification metrics
- Visualize the Decision Tree
- Analyze feature importance

---

## 🧠 What is a Decision Tree?

A Decision Tree is a **supervised machine learning algorithm** that can be used for both classification and regression problems.

For classification, the tree makes decisions by asking a series of questions about the input features.

For example:

```text
              Age > 30?
             /         \
           Yes          No
           /             \
      Income > 50K?     Class 0
       /      \
     Yes      No
     /         \
 Class 1      Class 0
