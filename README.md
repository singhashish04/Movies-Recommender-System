# 🎬 Movie Recommender System

A content-based movie recommendation system built using Python, pandas, and Streamlit.

## 🚀 Features

- Recommends similar movies based on genres, keywords, and overviews.
- Integrated with the OMDb API for movie plots and posters.
- Built with a clean and interactive UI using Streamlit.

## 📁 Files

- `main.py` — Streamlit app entry point
- `preprocess.py` — Cleans and vectorizes movie data
- `recommend.py` — Recommendation logic using cosine similarity
- `omdb_utils.py` — Fetches additional movie details using OMDb API
- `movies.csv` — Movie dataset
- `df_cleaned.pkl`, `cosine_sim.pkl` — Preprocessed files (generated)

## ⚙️ How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/singhashish04/Movies-Recommender-System.git
    cd Movies-Recommender-System
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Add your OMDb API key in `config.json`:
    ```json
    {
      "OMDB_API_KEY": "your_api_key_here"
    }
    ```

4. Run the preprocessing script:
    ```bash
    python preprocess.py
    ```

5. Start the Streamlit app:
    ```bash
    streamlit run main.py
    ```

## 🧠 Tech Stack

- Python
- pandas
- scikit-learn
- nltk
- Streamlit
- OMDb API
