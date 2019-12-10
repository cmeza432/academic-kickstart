                                                
+++ 
title="Classifier Feature"
+++

Second Iteration will be building a classifier feature. This classifier feature will use the user reviews about
movies and try to classify the genre based on the word used to describe the movies. I will be using the Naive 
Bayes Classifier algorithm for calculations. More detailed info here https://github.com/cmeza432/movie_recommender

Deployment:

Need to have Python Flask Version 1.1.1 or higher. To install just run on a terminal the command 
pip install flask. Once envrionment is set up, then you can run in a terminal and get the local host link to test out
from the machine locally.

Reference: https://geeksforgeeks.org/naive-bayes-classifiers/
Contribution to the reference would be seperating the data into calculatable numbers to perform the classifier
equation given, and be able to convert into the Numpy library built in calculations. Updating the code to the
Python 3 version as well.

Biggest challenge was doing the algorithm from scratch and adapting it to the equation. I had to split the data
and find unique words and group them into their respective genres. Once this was done then it was applying the 
Bayes Theorem to every genre and seeing which returned highest value.

The Bayes Theorem gets each word of the user input and applies the algorithm for each genre and calculating that value.
For example, if user entered "elf", "magic" then the algorithm will perform the values for the first genre. So if the first
genre on the list is "Action" then it would use the values for these words used in Action movies and then apply that equation
to get the value. Once this value is picked then it will store it into an array. Once this is done for all genres then it will
return the highest value and that genre it belongs too.

Evaluation:
This had to be done using Naive Bayes since when applying just the Bayes theorem I wouldn't get accurate results.

[Link to classifier here](http://cmeza432.pythonanywhere.com/text_search)
