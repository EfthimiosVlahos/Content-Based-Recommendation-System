# Movie Reccomendation System Project

![workflow](demo/6.jpeg)

Recommendation systems play a crucial role in today's fast-paced world, aiding users in making informed choices amidst a sea of content. Leveraging machine learning techniques, this project focuses on developing a content-based movie recommendation system enhanced with Natural Language Processing (NLP) capabilities.

## Key Highlights:
- **Content-Based Recommendation**: Utilizes characteristic information and item attributes to offer personalized movie suggestions.
  
- **NLP Techniques Integration**: Incorporates advanced NLP techniques to analyze user preferences and movie attributes, ensuring tailored recommendations.

- **Streamlit Web Application**: The project includes a Streamlit web application that seamlessly recommends various movies based on user interests.

## Dataset:
- [TMDB Movie Metadata Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

## Model Concept:
- Utilizes cosine similarity metric to measure document similarity, enabling effective movie recommendations.

## How to Run:
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movie python=3.7.10 -y
```

```bash
conda activate movie
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
```

Now run,
```bash
streamlit run app.py
```
