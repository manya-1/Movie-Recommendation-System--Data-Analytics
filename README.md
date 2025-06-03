# Movie-Recommendation-System--Data-Analytics

This is a content-based Movie Recommendation System built using Python and Natural Language Processing (NLP) techniques. It suggests top 10 similar movies based on a user’s input movie using TF-IDF vectorization and cosine similarity.

🔍 Overview
The system analyzes the metadata (plot summaries or textual features) of movies and recommends similar ones by calculating the similarity scores between them. It is a lightweight, interpretable solution ideal for personalized movie suggestions.

📌 Features
Content-based filtering using TF-IDF (Term Frequency–Inverse Document Frequency)

Cosine similarity for measuring movie similarity

Recommends Top 10 similar movies based on input title

Clean and modular codebase

🛠️ Tech Stack
Language: Python

Libraries:

pandas – Data handling

scikit-learn – TF-IDF vectorization and cosine similarity

numpy – Numerical computations

NLTK or re – (optional) Text preprocessing

🧠 How It Works
Load and clean the movie dataset.

Extract textual features (e.g., plot, genre, tags).

Apply TF-IDF vectorization to convert text into numerical vectors.

Compute cosine similarity between vectors.

Recommend movies with the highest similarity scores.
