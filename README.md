# 🌸 Anime Recommendation System 🎌  
**Find your next favorite anime, one recommendation at a time.**  

Welcome to your ultimate anime discovery companion! Whether you're a seasoned otaku or a curious newcomer, this system will help you uncover new anime tailored to your unique tastes — from underrated gems to top-rated classics.

<img width="745" height="499" alt="image" src="https://github.com/user-attachments/assets/e53e11e9-18d9-4098-b92e-212829428571" />

---

## 📖 What is this project about?

This project is a smart **Anime Recommendation System** built with Python. It uses real user data and anime metadata to suggest shows you might love based on what you (and others) already enjoy.

We combine the power of:
- 🔍 **Content-based filtering** (recommendations based on genre, type, etc.)
- 👥 **Collaborative filtering** (recommendations based on user behavior)

---

## 🧠 Why I built this

Anime is an enormous world — with thousands of titles out there, choosing what to watch next can be overwhelming. I wanted to create a system that mimics how a fellow anime fan might recommend something:  
*"You liked Death Note? Try Code Geass!"*  
*"Into romance with a supernatural twist? Watch Noragami!"*

Now, you can get those recs from code 💡

---

## 📦 Dataset

Pulled from Kaggle’s open source dataset:  
🎯 [Anime Recommendations Database](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database)

Files used:
- `anime.csv` — Contains anime metadata (genres, ratings, episodes)
- `rating.csv` — User ratings for each anime

---

## 🔥 Features

✨ **Data Cleaning & Exploration**  
📈 Visualizations (ratings, popularity, genre distribution)  
🌟 WordCloud of anime genres  
🎯 Popularity-based recommendations  
🎭 Genre-based and content-similarity recommendations  
🤝 Collaborative filtering using user preferences  
🧩 Cosine similarity, correlation matrices, and more

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Esraa0609/Anime-Recommendation-System.git
cd Anime-Recommendation-System
```

### 2. Install requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud
```

### 3. Run the notebook
```bash
jupyter notebook Anime_Recommendation_System.ipynb
```

---

## 🖼️ Sample Visualizations

- 📊 Genre frequency charts  
- 🌟 Top-rated anime bar graphs  
- ☁️ Genre WordClouds  
- 🔥 Correlation heatmaps for anime similarity  

---

## 🧬 How it works

### Content-Based Filtering
Recommends similar anime based on genre metadata using:
- Genre tokenization
- TF-IDF vectorization
- Cosine similarity scores

### Collaborative Filtering
Uses ratings from thousands of users to find patterns and suggest titles you haven’t seen yet.

---

## 📂 Folder Structure

```
📁 Anime-Recommendation-System/
├── 📓 Anime_Recommendation_System.ipynb
├── 📄 anime.csv
├── 📄 rating.csv
└── 📄 README.md
```

---

## 🗺️ What's Next?

- Add user interface using Streamlit or Flask 🖥️  
- Deploy online so fans can try it instantly 🌐  
- Integrate MAL or AniList API for live data 🔄  
- Support for manga recs too? 🤔


---

## 🌟 Love anime + code?

Drop a ⭐ on this repo if you like it — and feel free to open issues or ideas.  
Happy watching! 🍿🎬
