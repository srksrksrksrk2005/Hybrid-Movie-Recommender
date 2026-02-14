# Hybrid-Movie-Recommender
# Movie Recommendation System  
## Collaborative Filtering (ML0101EN)

## 📌 Project Overview

This project implements a **Movie Recommendation System** using **Collaborative Filtering**.

Collaborative Filtering recommends movies to users based on similarities between users or items (movies), using historical rating data.

The notebook demonstrates:

- Loading and exploring movie rating datasets  
- User–Item interaction matrix creation  
- Similarity computation  
- Generating movie recommendations  
- Evaluating recommendation results  

---

## 🎯 Objective

To build a recommender system that suggests movies to users based on:

- User similarity (User-Based Collaborative Filtering)  
OR  
- Item similarity (Item-Based Collaborative Filtering)

---

## 🧠 What is Collaborative Filtering?

Collaborative Filtering works on the assumption:

> Users who liked similar items in the past will like similar items in the future.

There are two main types:

### 1️⃣ User-Based Collaborative Filtering
- Finds similar users
- Recommends items liked by similar users

### 2️⃣ Item-Based Collaborative Filtering
- Finds similar movies
- Recommends movies similar to what the user liked

---

## ⚙️ Techniques Used

- Cosine Similarity  
- Pearson Correlation (if implemented)  
- Matrix operations with Pandas & NumPy  
- Rating prediction using weighted averages  

---

## 🛠️ Requirements

Install the following:

- Python (>= 3.8)
- Pandas
- NumPy
- Matplotlib (optional)
- Scikit-learn (if similarity functions are used)
- Jupyter Notebook

Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn notebook
```

---

## 📂 Project Structure

```
.
├── ML0101EN-RecSys-Collaborative-Filtering-movies.ipynb
├── README.md
```

---

## 🚀 How to Run

1. Download or clone the repository.
2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

```
ML0101EN-RecSys-Collaborative-Filtering-movies.ipynb
```

4. Run all cells sequentially.

---

## 🔍 Workflow

1. Load movie and rating datasets  
2. Clean and preprocess data  
3. Create user-item matrix  
4. Compute similarity scores  
5. Predict ratings  
6. Recommend top-N movies  

---

## 📊 Applications

- Netflix-style movie recommendation  
- E-commerce product recommendation  
- Music recommendation systems  
- Content personalization  

---

## 👤 Author

SADAM RAMAKRISHNA

---
