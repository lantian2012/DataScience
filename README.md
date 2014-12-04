DataScience
===========

Group Project for Data Science 

MovieTable: Aggregate data from 4 movie tables from rotten tomato. Duplicates are dropped.
NewMovieTable: Delete actors that show up less than 6 times. There are movies with no cast as their actors have been all deleted. Movies without critic rating are removed.

ActorTable: Wrangle data from MovieTable. Delete movies without critic rating.
NewActorTable: Delete actors that show up less than 6 times. 

ActorTable_clean/DirectorTable_clean/MovieTable_clean: remove directors with only 1 movie. Make the three tables consistent.

ActorTable_Twitter: add twitter data to NewActorTable. Note that this table does not use ActorTable_clean, so the movie data is not consistent with MovieTable_clean.

*_Twitter_clean: remove the actors without twitter data. delete a repeated actor.

*_Count: Added average column and count column. Except GenreTable, CriticTable, CriticGenreTable. 

