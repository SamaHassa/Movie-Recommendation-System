# Movie-Recommendation-System
# 🎬 Movie Recommendation System

A content-based recommendation system built using TF-IDF vectorization and cosine similarity to suggest movies similar to a given title. It leverages movie metadata such as genres, overviews, keywords, and cast information to compute similarity between films.

---

## 🔍 Features

- **Data Preprocessing:**
  - Cleans and processes metadata including genres, keywords, cast, and overview.
- **Text Processing:**
  - Utilizes NLTK’s `SnowballStemmer` and standard text cleaning techniques.
- **Feature Engineering:**
  - Merges multiple text-based features into a single tag.
  - Applies TF-IDF vectorization on combined tags.
- **Similarity Computation:**
  - Calculates cosine similarity between all movies based on their tag vectors.
- **Interactive Recommendation Function:**
  - Takes a movie title as input.
  - Displays the selected movie’s poster.
  - Returns a grid of similar movies with their posters and titles.
- **Visualization:**
  - Recommends movies in a clean, user-friendly grid layout.

---

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook

### 📦 Required Python Packages

```bash
pip install -r requirements.txt


scikit-learn for machine learning tools

NLTK for text processing
```
📂 Dataset
The system uses a movie metadata file movies.csv that includes:

Movie titles and IDs

Genres, overviews, and keywords

Cast and crew information (credits)

Popularity scores and vote metrics

Poster and backdrop image paths

🚀 How to Use
Clone this repository.

Install the required packages listed above.

Download the NLTK stopwords.

Place your movies.csv file in the root directory.

Open and run movie-recommendation-system.ipynb in Jupyter Notebook.

💻 Run with Streamlit
A Streamlit web interface for the movie recommendation system is already included in this project.
To launch the app, simply run the following command:

```bash
streamlit run "c:\DEPI\Recommendation system\My Work\Recom_stream.py"
```
💡 This will open a new browser window or tab with your interactive movie recommendation interface.




![image](https://github.com/user-attachments/assets/2df91e46-0a89-4bb7-bbd8-00dccf5b6297)
