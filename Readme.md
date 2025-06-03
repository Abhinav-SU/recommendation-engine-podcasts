# 🎧 Podcast Recommender System

A content-based engine that recommends similar podcasts by analyzing show descriptions.

## Table of Contents
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Author](#author)

## 🚀 Features
- TF-IDF and CountVectorizer embeddings
- Cosine similarity scoring
- Cleaned podcast metadata
- Interactive Jupyter notebook for experimentation

## 📁 Dataset
Place your dataset in `data/podcasts.csv`. The CSV should contain:
- `title` – podcast title
- `description` – text used for similarity comparison
- `categories` – optional comma-separated categories

## 📦 Installation
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🧪 Usage
1. Add `podcasts.csv` to the `data/` folder.
2. Launch the notebook:
   ```bash
   jupyter notebook recommendation_engine.ipynb
   ```
   Follow the notebook to build the similarity matrix and generate recommendations.

## ✍️ Author
Abhinav Bajpai  
[GitHub](https://github.com/Abhinav-SU) • [LinkedIn](https://www.linkedin.com/in/abhinavbajpai0296)

---

## 🔖 Tags
`machine-learning` `recommendation-system` `nlp` `cosine-similarity` `tf-idf` `python` `podcasts`
