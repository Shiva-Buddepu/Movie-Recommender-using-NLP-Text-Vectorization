# Movie Recommender using NLP & Text Vectorization

It recommends similar movies based on movie metadata such as **overview, genres, keywords, cast, and crew**.
Unlike collaborative filtering, this system does **not require user ratings** and works purely on the textual content of movies.

## Features
- Preprocess movie metadata and create a combined **tags** feature
- Text vectorization using **CountVectorizer** (bag-of-words model)
- Compute **cosine similarity** between movies
- Recommend top 5 similar movies for a given movie
- Save processed data and similarity matrix using **Pickle** for later use
- Supports easy deployment and usage
