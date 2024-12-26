# AI for Readers: Personalized Book Recommendations

## Overview
This repository contains a book recommendation system using **collaborative filtering** techniques. The system explores memory-based and model-based approaches to offer personalized book suggestions.

---

## Key Features

### Collaborative Filtering
A technique to recommend books based on users' past interactions, without relying on item-specific features like author or genre.

### Techniques Used
- **Memory-Based Approaches**  
  Simple and effective for smaller datasets, calculating similarity between users or items.
  
- **Model-Based Approaches**  
  Uses models like matrix factorization or neural networks, ideal for larger datasets.

### Advanced Methods
- **Non-Negative Matrix Factorization (NMF)**  
  Decomposes user-item matrices to extract latent features, improving recommendation accuracy.
  
- **Non-Linear Dimensionality Reduction (e.g., t-SNE)**  
  Reduces data complexity while maintaining important patterns in high-dimensional data.
  
- **Clustering-Based Approaches**  
  Groups similar users/items to refine recommendations.

---

## Objective
Develop a scalable book recommendation system that enhances precision and user satisfaction through advanced machine learning techniques.

---

## Demo
This project includes an interactive demo using **FastAPI** and **Streamlit**:

- **FastAPI**: Backend API for generating personalized book recommendations.
- **Streamlit**: User interface for interacting with the system and viewing suggestions.

---

## Steps to Run the Project

### Prerequisites
1. **Visual C++ Build Tools** (for `scikit-surprise`):
   - Install from [Microsoft Visual C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/).
   
2. **Required Libraries**:
   Install dependencies using:
   ```bash
   pip install numpy pandas joblib ydata-profiling scikit-surprise
   pip install scikit-learn nltk matplotlib seaborn pgmpy
   pip install torch streamlit-aggrid
