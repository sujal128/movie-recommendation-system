<h1 align="center">🎬 Movie Recommendation System — Data Science & Machine Learning Project</h1>
<h3 align="center">Content-Based & Collaborative Filtering Recommender System</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=black"/>
  <img src="https://img.shields.io/badge/Machine_Learning-00C853?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 🧠 Overview
This project builds an intelligent **Movie Recommendation Engine** using:
- **Content-Based Filtering** (movie-to-movie similarity)
- **Collaborative Filtering** (user-to-movie recommendation)

Designed similar to real systems used by Netflix, Amazon Prime & YouTube.

---

## 📂 Repository Structure
```
📦 movie-recommendation-system
│
├── movie_recommendation_system.ipynb   → Main Jupyter notebook
├── requirements.txt                    → Dependencies
└── README.md                           → Documentation
```

---

## 🧮 Methods Implemented

### 🔹 1. Content-Based Recommendation
Uses:
- `CountVectorizer` for text vectorization
- `CosineSimilarity` to compute movie similarity

Example capability:
```
Because you watched Inception → You may like Interstellar, The Matrix, The Dark Knight
```

### 🔹 2. Collaborative Filtering
Uses user–movie rating matrix to recommend movies users haven’t rated yet.

Example output:
```
Recommended for User 1 → Interstellar, Avengers Endgame, La La Land
```

---

## 🔧 Tech Stack

| Category | Tools |
|----------|--------|
| Language | Python |
| Libraries | Pandas, NumPy, Scikit-Learn |
| ML Algorithms | Cosine Similarity, Collaborative Filtering |
| Platform | Jupyter Notebook / Google Colab |

---

## ▶️ How to Run

### Install dependencies
```bash
pip install -r requirements.txt
```

### Open notebook
```bash
jupyter notebook movie_recommendation_system.ipynb
```

Run cells sequentially and test output.

---

## 📌 Example Usage

### Similar movies recommendation
```python
recommend_by_movie("Inception", top_n=5)
```

### Personalized user recommendations
```python
recommend_for_user(user_id=1, top_n=5)
```

---

## 🏁 Key Outcomes
- Movie similarity recommendation engine
- User-based collaborative filtering recommender
- Demonstrates real industry recommender logic
- Portfolio-ready ML system for recruitment & internships

---

## 🛠 Future Enhancements
- Add Surprise / SVD algorithm
- Deploy via Streamlit / Flask
- Use large MovieLens dataset
- Add ranking metrics (RMSE / MAE)

---

## 👤 Author
**Sujal Singh**  
_Data Science • Machine Learning • AI & Recommender Systems_

<p align="center">
  <a href="https://github.com/sujal128"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/sujal-singh-40657728b/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<p align="center"><b>“Data turns experience into intelligence — recommend, predict, innovate.”</b></p>
