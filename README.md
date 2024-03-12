

This repository contains code for generating movie recommendations using content-based filtering. The code processes movie data from two datasets, `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`, and then constructs a content-based recommendation system based on movie descriptions, genres, keywords, cast, and crew information.

### Files Description:
- **movie_recommendation.ipynb**: Jupyter Notebook containing Python code for data preprocessing, feature extraction, and building a recommendation system.
- **movies.pkl**: Pickle file containing the preprocessed movie data.
- **tmdb_5000_movies.csv**: Dataset containing information about movies.
- **tmdb_5000_credits.csv**: Dataset containing credits information about movies.

### Libraries Used:
- `numpy` (version 1.19.5): Used for numerical computations.
- `pandas` (version 1.3.3): Used for data manipulation and analysis.
- `scikit-learn` (version 0.24.2): Used for machine learning tasks such as vectorization and cosine similarity calculations.
- `nltk` (version 3.6.5): Used for natural language processing tasks such as stemming.

### Usage:
1. Clone the repository to your local machine.
2. Ensure you have the required libraries installed. You can install them using pip:
```
   pip install numpy pandas scikit-learn nltk
   ```
3. Run the Jupyter Notebook `movie_recommendation.ipynb` to execute the code.
4. The notebook will preprocess the data, build a content-based recommendation system, and save the processed data to a pickle file (`movies.pkl`).
5. You can use the generated `movies.pkl` file for making movie recommendations in your own applications.

### Note:
- Make sure to have the `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` files in the same directory as the notebook.
- The code preprocesses the data, generates movie tags, and calculates cosine similarity between movies based on these tags to provide recommendations.
- The recommendation system is solely based on the content of the movies and does not take into account user preferences or ratings.

Feel free to explore and modify the code as per your requirements. If you have any questions or suggestions, please feel free to reach out.
