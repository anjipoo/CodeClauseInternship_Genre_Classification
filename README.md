# Movie Genre Prediction

Predict the genre of a movie based on its plot summary and other features using Natural Language Processing (NLP).

---

## Project Overview

This project uses NLP techniques to classify movie genres from their plot descriptions. It leverages Python libraries such as NLTK for text preprocessing, and Scikit-learn's Logistic Regression model for classification.

The dataset includes movie descriptions and genres, and the model is trained to predict among the top 5 genres:

- Comedy  
- Documentary  
- Drama  
- Horror  
- Short  

---

## Features

- Text cleaning and preprocessing (lowercasing, stopword removal, lemmatization) using NLTK  
- TF-IDF vectorization for feature extraction  
- Logistic Regression classification  
- Performance evaluation with accuracy, classification report, and confusion matrix  
- Interactive genre prediction on new plot descriptions  

---

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/anjipoo/CodeClauseInternship_Genre_Classification.git
cd CodeClauseInternship_Genre_Classification
```
2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv .venv
.\.venv\Scripts\activate
```
3. Install dependencies:

```bash
pip install -r requirements.txt
```
