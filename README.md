# Jester Recommendation

Building a simple recommendation system based on the jester data set: consists of roughly 25K users ratings of jokes, a matrix with dimensions 24983x101.

According to the documentation of this data source:

* Ratings are real values ranging from -10.00 to +10.00 (the value "99" corresponds to "null" = "not rated").
* One row per user
* The first column gives the number of jokes rated by that user. The next 100 columns give the ratings for jokes 01 - 100.
* The sub-matrix including only columns {5, 7, 8, 13, 15, 16, 17, 18, 19, 20} is dense. Almost all users have rated those jokes.
* Also included is a test set of (roughly) the same size and format
