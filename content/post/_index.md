<!-- ---
# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/img/` folder).
header:
  caption: "Movie Recommender App"
  image: ""
--- -->

                                                About Movie Recommender App

This movie recommender app uses practices from the Data Mining Field to use different methods for information retrieval. The webapp will use a Text Search, Classifier and Image Captioning to return results based on user input. It will run using Python Flask version 1.1.1. This will be done in three different iteration. First Iteration will be the text search feature. The dataset used will be the IMDB Reviews dataset which is roughly about 150MB in size and has over 50k reviews with both a test set and training set split into 25k each. User will type in text paragraph and it will rank using Cosine Similarity of each document with text input.


Detailed info on how it works here: https://github.com/cmeza432/movie_recommender

Reference: http://www.tfidf.com/
Contribution: Using Numpy to do better calculation when doing TFIDF by doing vector multiplication on column to column
instead of doing each dimension seperate. Implementing into python.


Biggest challenge was getting the libraries once local app was finished so it can run on server. Solution was to set up environent  and once in that environment, download all libraries, then link it to the project while selecting that evnironment in web app page.

Compile time without caching tfidf matrix:
Without stop words: 30-40 seconds
With stop words: 20-30 seconds

Compile time with caching tfidf matrix:
Without stop words: 10-15 seconds
With stop words: 3-8 seconds
 

[Link to app here](http://cmeza432.pythonanywhere.com)
