# Phase 2 Project: Yi-Wei Liu

## Overview and Business Understanding
A hypothetical company has decided to create a new movie studio, and would like to explore what types of films are currently doing the best at the box office. In this notebook, I investigate the statistical relationship between various movie attributes - including run-time, genre and month of release - and worldwide box-office gross. Specifically:

1. Run-time: Is the movie's length (in minutes) associated with higher worldwide gross?
2. Genre: Are there any genres associated with higher worldwide gross? For the scope of this project, we will only look at the top three genres by frequency.
3. Month of release: Which months of the year are associated with higher worldwide gross?
   
The main documents in this repository include:  
1) this README file;
2) the non-technical presentation summarizing the conclusions to company's management ([presentation.pdf][LINK HERE);
3) the Jupyter notebook showing the data preparation and analysis ([student.ipynb](LINK HERE));  

## Data Analysis and Conclusions
The movie's run-time, genre and release month all have a statistically significant relationship (p < 0.05) with worldwide gross. 

Run-time: Every additional minute of run-time is associated with 1,910,000 incremental worldwide gross. This does make some intuitive sense: many of the top-grossing superhero and epic drama movies tend to be over 2 hours long. However, the relationship is unlikely to be linear.

Genres: If the movie is a comedy, it will make an additional 41,750,000 in worldwide gross compared to a non-comedy and non-action movie with the same run-time and month of release. If the movie is an action movie, it will make an additional 159,700,000 compared to an equivalent non-action, non-comedy movie.

Release month: The "control months" are those not included in the regression, i.e. February, March, April, November and December. If the movie is released in October, it will make 49,630,000 less in worldwide gross compared to the equivalent movie in a control month. The same kind of interpretation is applicable to movies released in September (43,230,000 less), August (35,710,000 less), July (35,320,000 more), June (63,250,000 more), May (56,520,000 more) and January (48,070,000 less) 

In summary, based on the results of this regression, to make a higher-grossing movie we want to: 1) increase the run-time; 2) make it an action movie; 3) release it in June.

HOWEVER, drawbacks with the regression include:...
