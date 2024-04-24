# FDAB Team 2 Project
## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on movies from the [IMDB Movies Dataset](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows).

With the vast amounts of digital content available in today's world, people often find it difficult to find something that they are interested in watching. Our project aims to solve that problem by providing movie recommendations based on a given user input.
Our project also aims to predict IMDB ratings of movies given information about the movie.

## Individual Contribution
- @Exhilion (Sam Chern Kai, Chester) - Regression Model for prediction of IMDB Rating, Sequence Matcher for typographic errors
- @dhvl2004 (Duong Hoang Vu Lam) - Exploratory Data Analysis, data preparation and cleaning
- @exkitty1 (Ng Zi Yuan) - CountVectorizer for counting word occurences, CosineSimilarity for comparing 2 movies, menu functions

## Problem Definition
- Are we able to compare the similarity between two movies based on the dataset?
- How are we able to determine what movies to recommend?
- Can we predict the IMDB ratings for a movie using data from similar movies?
- What regression model would best suit this prediction?

## Models Used
- SequenceMatcher
- CountVectorizer
- CosineSimilarity
- Random Forest

## Conclusion
-Able to suggest the correct movie if user made a typographical error
- Able to accurately recommend the top 5 similar movies based on the contents of the movie and its genre
- Random Forest Regression is accurate and reliable to predict IMDB ratings based on the given variables
- Strong correlation between the genre, director and stars and IMDB ratings

## Key takeaways
- Sequence Matcher
- Count Vectorizer
- Cosine Similarity
- Random Forest Regression Model
- Data cleaning techniques to streamline machine learning

## Contents of This Repository
### Presentation Slides
The slides are part of a short 10-minute presentation on the problem definition, exploratory data analysis, core analysis and the machine learning models we used and the conclusion which comprises of what we learned, the outcome of our project and our data-driven insights.
### SC1015_MiniProject
This contains the entire codebase involving data preparation and cleaning, exploratory data analysis and the machine learning models. The different models work together to provide the best movie recommendations based on the user input.

## References
- https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows
- https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html
- https://www.machinelearningplus.com/nlp/cosine-similarity/
