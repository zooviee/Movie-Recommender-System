# 🎬 Movie Recommender System

This project is a content-based movie recommender built with Streamlit and scikit-learn. It suggests similar movies based on the one you input — using movie metadata like title, genres, and overview to calculate similarity.

## 🔍 Features
- Recommends movies similar to the selected one
- Uses cosine similarity on TF-IDF/CountVectorizer matrix
- Displays movie posters via TMDb API
- Interactive Streamlit interface (app.py)
- Exploratory data analysis in Jupyter (movie_recommender.ipynb)

## 🗂 Project Structure

``` bash
├── artifacts/                   # Pickled model objects, similarity matrix, etc.
├── data/                        # Raw or cleaned movie metadata
├── src/                         # Python modules for preprocessing, recommendations
├── app.py                       # Streamlit app
├── movie_recommender.ipynb      # Notebook with EDA & development
├── requirements.txt             # Python dependencies
├── Procfile                     # Heroku deployment config
```


## 🚀 How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/zooviee/movie-recommender-system.git
cd Movie Recommender System
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movies python=3.12 -y
```

```bash
conda activate movies
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
#run this file to generate the models

movie_recommender.ipynb
```

Now run,
```bash
streamlit run app.py
```


```bash
Author: Oluwaseyi Akinsanya
Data Scientist
Email: seyiakinsanya1999@gmail.com

```
