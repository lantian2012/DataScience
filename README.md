
#Group Project for Data Science 
##What to Watch: Something You Don’t Know about Rottentomatoes.com
-----------------

Peiheng Hu, Tian Lan, Xiaoan Wang

### Overview

We are a group of three film buffs. We discuss movies, get information about the latest films and upcoming releases, and hang out at movie theaters. We love all kinds of movies including those independent films that failed miserably in the box office. With this project we not only will find the secret common factors behind successful movies, but also will re-examine whether the box office is the only matrix to define a good movie. There are some movies we will go and see no matter what the critics say. Maybe it's a big dumb comedy and we feel like a laugh or there is one actor we really love. Conversely there are times when there are ten movies showing during holiday season and we browse out Rottentomato to seek critics’ suggestions.

### File Description

- Data Retrieval Files

  - Training Data  
    DataRetrieval.ipynb  
    DataRetrieval-Boxoffice.ipynb  
    DataRetrieval-Counted.ipynb  
    DataRetrieval-CriticData.ipynb

  - Test Data  
    DataRetrieval2014.ipynb  
    DataRetrieval-Boxoffice2014.ipynb  
    DataRetrieval-Counted2014.ipynb  

  - Data Summary  
    Dataset.ipynb

- Analysis Files  
  ExploratoryAnalysis.ipynb
  D3TextOutput.ipynb
  Critics_Customer_Rating_Analysis.ipynb  
  Regression.ipynb  
  Kmean.ipynb

- Data Files
  MovieTable: Aggregate data from 4 movie tables from rotten tomato. Duplicates are dropped.  
  NewMovieTable: Delete actors that show up less than 6 times. There are movies with no cast as their actors have been all deleted. Movies without critic rating are removed.  
  ActorTable: Wrangle data from MovieTable. Delete movies without critic rating.  
  NewActorTable: Delete actors that show up less than 6 times.  
  ActorTable_clean/DirectorTable_clean/MovieTable_clean: remove directors with only 1 movie. Make the three tables consistent.  
  ActorTable_Twitter: add twitter data to NewActorTable. Note that this table does not use ActorTable_clean, so the movie data is not consistent with MovieTable_clean.  
  CriticRaw: Raw critic data from rotten tomatoes.  
  CriticTable: Aggregate data from CriticRaw.  
  *_Twitter_clean: remove the actors without twitter data. delete a repeated actor.  
  *_Fixed: fix the inconsistency on *_Twitter_clean.  
  *_Count: Added average column and count column. Except GenreTable, CriticTable, CriticGenreTable.   
  *_Pred: Add the sum of box office for actors and directors.  

