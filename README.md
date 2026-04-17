# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** that suggests similar movies using machine learning techniques like **TF-IDF** and **cosine similarity**.

---

## 📌 Project Overview

This project recommends movies by analyzing their metadata (such as overview, genres, etc.) and finding similarities between them.

It uses a **content-based filtering approach**, meaning recommendations are based on movie features rather than user ratings.

---

## 🚀 Features

- 🔍 Search movies by title  
- 🎯 Get top similar movie recommendations  
- 🧠 Uses TF-IDF vectorization  
- 📊 Cosine similarity-based recommendations  
- 💻 Simple interface using Streamlit  

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│
├── app.py                 # Streamlit app
├── main.py                # Recommendation logic
├── movies.ipynb           # Model development
│
├── movies_metadata.csv    # Dataset
│
├── df.pkl                 # Processed data
├── indices.pkl            # Title to index mapping
├── tfidf.pkl              # TF-IDF model
├── tfidf_matrix.pkl       # Vectorized data
│
├── requirements.txt       # Dependencies
└── .gitignore
```


---

## ⚙️ How It Works

1. Load dataset  
2. Clean and preprocess data  
3. Convert text into vectors using TF-IDF  
4. Compute cosine similarity between movies  
5. Recommend top similar movies  

---

## 🧪 Installation & Setup

### 1. Clone the repository
```
git clone https://github.com/AmanKumarAyush007/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```


### 2. Create virtual environment

```
python -m venv venv
OR
py -3.11 -m venv venv  # for python 3.11
```


### 3. Activate environment
**Windows:**

```
venv\Scripts\activate
```

**Linux/Mac:**
```
source venv/bin/activate
```

### 4. Install dependencies
```
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Run Python Script
```
python main.py
```
### Run Streamlit App  
```
streamlit run app.py
```

---

## 📊 Model Details

- Vectorization: TF-IDF  
- Similarity: Cosine Similarity  
- Approach: Content-Based Filtering  

---

## 🔮 Future Improvements

- Add collaborative filtering  
- Hybrid recommendation system  
- Add movie posters using TMDB API  
- Deploy project online  


---

## 📜 License

This project is licensed under the MIT License.

---

