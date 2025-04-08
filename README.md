# 📚 Book Recommender System

A content-based book recommendation system built using TF-IDF and cosine similarity. It suggests similar books based on the title input, helping users discover new reads aligned with their interests.

## 🔍 Overview

This project utilizes:
- TF-IDF vectorization of book titles
- Cosine similarity to find books most similar to a given one
- Book cover image rendering for a richer visual experience

🧰 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

## 📁 Dataset Overview

The dataset used includes:
- `Books.csv`: Book metadata
- `Users.csv`: User demographic info
- `Ratings.csv`: Explicit ratings given by users

  ## 🧠 How It Works

1. **Data Cleaning**: Removes duplicates, fills missing values.
2. **Filtering Active Users**: Filters users and books with sufficient number of ratings.
3. **Model Building**: Uses K-Nearest Neighbors (KNN) to find similar books.
4. **User Input**: Returns top recommended books based on a selected book.

---
