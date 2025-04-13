
# Mentor Recommendation System

This project is designed to assist CLAT aspirants by recommending personalized mentors based on user preferences and mentor profiles using a content-based filtering approach.

## Project Summary

The **Mentor Recommendation System** leverages:
- **OneHotEncoder** for handling categorical features (e.g., Subject expertise, Experience level, Region)
- **K-Nearest Neighbors (KNN)** from `sklearn.neighbors` to identify mentors most similar to the user's preferences

###  Workflow Overview:
1. Load mentor dataset with features like specialization, availability, and region.
2. Encode categorical features using **OneHotEncoding**.
3. Fit the **Nearest Neighbors model**.
4. Accept user input (their preferences).
5. Recommend top-N most similar mentors based on vector similarity.

---

##  Setup Instructions

### 1. Environment Requirements
Python version: >=3.7 (Recommended: 3.8 or 3.9)
Jupyter Notebook: >=6.0
OS Compatibility: Windows, macOS, Linux

### 2. Install the following libraries:
pip install pandas==1.5.3 scikit-learn==1.2.2 notebook==6.5.4

### 3. Run the Jupyter Notebook
jupyter notebook Mentor_Recommendation_System.ipynb

---

## Requirements

- Python 3.7+
- pandas
- scikit-learn
- jupyter (for running `.ipynb`)

---
