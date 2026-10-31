# Movie-Recommendation-System
# 🎬 Movie Recommendation System

## 1. Project Overview

The Movie Recommendation System is a machine learning project developed using Python that recommends movies to users based on their favourite movies and genres.

The system uses **Content-Based Filtering** to analyse movie genres and calculate similarities between movies. Based on these similarities, it suggests movies that users may also enjoy.

The main objective of this project is to make movie discovery easier by providing personalised movie recommendations.

## 2. Features

- **Movie Search:** Users can enter their favourite movie name.
- **Genre-Based Recommendation:** Recommends movies based on similar genres.
- **Similarity Calculation:** Uses Cosine Similarity to measure similarity between movies.
- **Top Recommendations:** Displays the top 3 recommended movies.
- **User-Friendly Input:** Accepts movie names through the terminal.
- **Movie Dataset:** Uses a structured dataset containing movie titles and genres.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data manipulation and processing |
| Scikit-learn | Machine learning and similarity calculation |
| CountVectorizer | Converts movie genres into numerical features |
| Cosine Similarity | Measures similarity between movies |
| Jupyter Notebook / VS Code | Development environment |
| Git & GitHub | Version control and project hosting |

## 4. Dataset

The project uses a movie dataset containing information about movie titles and their genres.

**Dataset Attributes:**

- `title`: Name of the movie.
- `genres`: Categories associated with the movie, such as Action, Adventure, Romance, Drama and Sci-Fi.

For the initial implementation, a small sample dataset is used.

**Dataset Source:**

[MovieLens Dataset – GroupLens](https://grouplens.org/datasets/movielens/)

A larger MovieLens dataset can be integrated to improve the number and variety of recommendations.

## 5. Model Architecture

The project uses **Content-Based Filtering** with CountVectorizer and Cosine Similarity.

### Working Process

1. **Data Collection:** Collect movie titles and their genres.
2. **Data Preprocessing:** Load and organise movie information using Pandas.
3. **Feature Extraction:** Use CountVectorizer to convert movie genres into numerical vectors.
4. **Similarity Calculation:** Apply Cosine Similarity to calculate similarities between movies.
5. **Movie Recommendation:** Identify movies with the highest similarity scores.
6. **Output:** Display the top 3 recommended movies.

### Algorithm Used

**Cosine Similarity**

Cosine Similarity measures the similarity between two numerical vectors.

The formula is:

Cosine Similarity = (A · B) / (||A|| × ||B||)

A higher similarity score indicates that two movies have more similar genre features.

## 6. Results

The system successfully recommends movies based on the genre of the movie entered by the user.

**Sample Input:**

```text
Enter your favourite movie: Avengers
```

**Sample Output:**

```text
Recommended Movies:

Iron Man
Thor
Avatar
```

The results demonstrate that the system can identify movies with similar genre characteristics and generate relevant recommendations.

*Note: Results are based on a small sample dataset and are intended to demonstrate the working of the recommendation algorithm.*

## 7. How to Run

Follow these steps to run the project on your computer.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### Step 2: Open the Project Folder

```bash
cd movie-recommendation-system
```

### Step 3: Install Required Libraries

```bash
pip install pandas scikit-learn
```

### Step 4: Run the Python Program

```bash
python movie_recommender.py
```

### Step 5: Enter Your Favourite Movie

Enter a movie name when prompted.

The system will display the top 3 recommended movies.

## 8. Repository Structure

```text
Movie-Recommendation-System/
│
├── movie_recommender.py
│
├── dataset/
│   └── movies.csv
│
├── README.md
│
└── requirements.txt
```
## 👨‍💻 Author

Gargi Kumar Choudhery

GitHub: https://github.com/Robert22620010



