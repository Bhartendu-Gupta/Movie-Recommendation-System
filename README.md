# 🎬 Movie Recommendation System

A Machine Learning-powered **Content-Based Movie Recommendation System** that recommends movies similar to a user's favorite movie using **Natural Language Processing (NLP)** and **Cosine Similarity**. The application is built with **Python** and deployed using **Streamlit** to provide an interactive and user-friendly web interface.

---

## 📌 Overview

Finding the right movie to watch can be overwhelming. This project helps users discover similar movies based on content such as genres, keywords, cast, crew, and overview. Instead of relying on ratings or popularity, it analyzes movie metadata and recommends the most relevant movies.

---

## 🚀 Features

- Content-Based Movie Recommendation
- NLP-based Feature Engineering
- Text Vectorization using CountVectorizer
- Cosine Similarity for Recommendation
- Displays Top Similar Movies
- Fetches Movie Posters using TMDB API
- Interactive Streamlit Web Interface
- Fast and Responsive Predictions

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Machine Learning | Scikit-learn |
| NLP | NLTK, CountVectorizer |
| Data Analysis | Pandas, NumPy |
| Frontend | Streamlit |
| API | TMDB API |
| Model Storage | Pickle |
| Version Control | Git & GitHub |

---

## 📂 Dataset

This project uses the **TMDB 5000 Movie Dataset**, which contains information about thousands of movies including:

- Movie Title
- Genres
- Keywords
- Cast
- Crew
- Overview

The recommendation engine combines these features to generate meaningful movie suggestions.

---

## ⚙️ How It Works

1. Load movie dataset.
2. Perform data preprocessing.
3. Combine important movie metadata.
4. Apply text preprocessing.
5. Convert text into vectors using **CountVectorizer**.
6. Calculate similarity using **Cosine Similarity**.
7. Recommend the most similar movies.
8. Fetch movie posters using the **TMDB API**.
9. Display recommendations through a Streamlit web application.

---

## 📁 Project Structure

```
Movie-Recommendation-System/
│
├── app.py
├── Movie Recommender System.ipynb
├── movies.pkl
├── movie_dict.pkl
├── similarity.pkl
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Bhartendu-Gupta/Movie-Recommendation-System.git
```

Move into the project directory

```bash
cd Movie-Recommendation-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 💻 Demo

Enter your favorite movie name and click **Recommend**.

The application will:

- Find similar movies
- Display movie posters
- Recommend the most relevant movies instantly

---

## 📸 Screenshots

> Add screenshots of your Streamlit application here.

Example:

- Home Page
- Recommendation Results

---

## 📈 Future Improvements

- User Authentication
- Hybrid Recommendation System
- Collaborative Filtering
- Search Autocomplete
- Genre-wise Filtering
- Personalized Recommendations
- Better UI/UX
- Docker Deployment

---

## 🎯 Learning Outcomes

During this project, I learned:

- Content-Based Recommendation Systems
- Natural Language Processing (NLP)
- CountVectorizer
- Cosine Similarity
- Feature Engineering
- Machine Learning Workflow
- Streamlit Deployment
- TMDB API Integration
- Git & GitHub
- Model Serialization using Pickle

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork this repository and submit a pull request.

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is developed as part of my machine learning portfolio to demonstrate practical skills in Python, NLP, Scikit-learn, and Streamlit. The source code is available for learning and reference purposes.
