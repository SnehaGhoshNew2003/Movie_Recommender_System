# Movie Recommendation System

This project builds a **content-based movie recommendation system** that suggests similar movies based on user input.

## Features
- **Text Preprocessing:** Uses NLP techniques to clean movie descriptions.
- **Feature Extraction:** Converts text into numerical format using `CountVectorizer`.
- **Similarity Calculation:** Computes movie similarity using `cosine_similarity`.
- **Recommendation Engine:** Suggests movies similar to a given input movie.
- **Model Persistence:** Saves processed data for future use.

## Technologies Used
- **pandas** (Data manipulation)
- **numpy** (Numerical operations)
- **nltk** (Natural language processing)
- **scikit-learn** (Vectorization & similarity computation)
- **pickle** (Model storage)

## Installation
Install the required dependencies:
```bash
pip install pandas numpy scikit-learn nltk
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Movie_Recommender.git
cd Movie_Recommender
```
2. Run the Jupyter Notebook:
```bash
jupyter notebook Movies_Recommended_System.ipynb
```
3. Follow the notebook instructions to preprocess data, compute similarities, and get recommendations.

## Example Output
- **Input:** Movie title (e.g., "Inception")
- **Output:** List of recommended movies

## Contributing
Feel free to submit issues or pull requests to improve this project.
