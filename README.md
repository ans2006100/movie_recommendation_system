# 🎬 Movie Recommendation System

## 📌 Overview

This project is a **Content-Based Movie Recommendation System** built using **Python** and **Natural Language Processing (NLP)** techniques. It recommends movies similar to a user's selected movie by analyzing movie metadata such as genres, keywords, cast, crew, and overview.

---

## 🚀 Features

* Recommend similar movies based on content.
* Uses NLP for text preprocessing.
* Combines movie overview, genres, keywords, cast, and director information.
* Calculates similarity using **Cosine Similarity**.
* Simple and efficient recommendation engine.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Pickle
* Jupyter Notebook

---

## 📂 Dataset

The project uses the TMDB 5000 Movie Dataset:

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

---

## ⚙️ Project Workflow

1. Load the TMDB datasets.
2. Merge movie and credits datasets.
3. Select important features.
4. Handle missing values.
5. Extract genres, keywords, cast, and director.
6. Perform text preprocessing.
7. Create tags by combining all important features.
8. Apply CountVectorizer.
9. Compute Cosine Similarity.
10. Recommend the top similar movies.

---

## 📊 Machine Learning & NLP Concepts

* Content-Based Filtering
* Text Preprocessing
* Tokenization
* Stemming
* Bag of Words
* CountVectorizer
* Cosine Similarity

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries:

   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook.
4. Run all cells.
5. Select a movie and get recommendations.

---

## 📁 Project Structure

```
movie-recommendation-system/
│── Movie Recommendation.ipynb
│── tmdb_5000_movies.csv
│── tmdb_5000_credits.csv
│── requirements.txt
│── README.md
│── movies.pkl
│── similarity.pkl
```

---

## 🎯 Future Improvements

* Build a Streamlit web application.
* Add movie posters using the TMDB API.
* Improve recommendations using hybrid filtering.
* Deploy the application online.

---

## 👩‍💻 Author

**Anshika Sethi**

B.Tech CSE (AI & ML)

Passionate about Artificial Intelligence, Machine Learning, NLP, and Computer Vision.

---

## ⭐ If you found this project useful, consider giving it a Star!
