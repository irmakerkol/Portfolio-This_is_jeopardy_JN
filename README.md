# Jeopardy Dataset Analysis & Text Normalization

This project demonstrates data cleaning, feature engineering, and basic natural language processing (NLP) on a real-world trivia dataset sourced from Jeopardy! questions. It’s an ideal showcase of essential data science techniques, including handling unstructured text, normalization, and basic string matching logic for answer evaluation.

---

## 🧠 Project Overview

In this notebook, I explore and preprocess a dataset containing historical Jeopardy! questions and answers. The focus is on:

- Cleaning messy real-world text data
- Tokenization and normalization
- Designing logic to compare user-input answers to ground truth
- Working with categorical, textual, and contextual features

This project illustrates how data science workflows handle raw data and derive structure from unstructured formats, a critical skill in many real-world applications.

---

## 📂 Dataset

The dataset used comes from an online archive of Jeopardy! questions. It includes:

- **Show Number**
- **Air Date**
- **Round**
- **Category**
- **Value**
- **Question**
- **Answer**

---

## 🔍 Key Steps & Techniques

### 1. Data Loading & Initial Exploration
- Loaded the dataset using `pandas`
- Identified missing data, duplicate entries, and structural inconsistencies

### 2. Data Cleaning & Preprocessing
- Removed formatting artifacts from text
- Standardized column names
- Cleaned dollar values for numeric conversion

### 3. Text Normalization for Comparison
- Implemented case normalization
- Removed punctuation and stop words
- Tokenized answers and user inputs for soft comparison
- Designed a rule-based evaluation function to score user answers against ground truth


### 4. Evaluation Logic Design
- Built a system to match user input with answer key using normalized tokens
- Allowed minor variations in input to still be accepted as correct
- Tracked user accuracy

---

## 🧰 Technologies Used

- Python
- Pandas
- Regular Expressions
- Basic NLP (manual tokenization, normalization)
- Jupyter Notebook

---

## 🎯 Learning Highlights

- Data cleaning and preparation for modeling or human interaction
- NLP fundamentals using only Python (without heavy frameworks)
- Creating data-driven logic for evaluation tasks
- Handling string similarity and answer validation challenges

---


