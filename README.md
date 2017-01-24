# movielens
Investigate on movielens 20m database to answer a simple question: which movie(s) has to be recommended to somebody who've just seen Inferno (2016), directed by Ron Howard.

Content:
-- movielens.R:
Main R script used for the investigation. It is divided in different part, namely the data reading, a simple content-based recommendation based on data exploration, and some machine learning technique implementation aiming to give more structured answer to the initial question
-- figs
Repository containing figures generated during database process
-- data
Repositoy containing initial Movielens data
---- movies.csv:
Movielens database dedicated to movies (movieId, title, genres)
---- ratings.csv:
Movielens database dedicated to user ratings (userId, movieId, ratings, timestamp)
---- tags.csv:
Movielens database dedicated to movie tags (userId, movieId, tag, timestamp)
---- genome-tags.csv:
Movielens database dedicated to tags considered in the genome (id, tag)
---- genome-scores.csv:
Movielens database dedicated to genome tags for each movie (tagId, movieId)
