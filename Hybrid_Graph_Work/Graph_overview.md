
## Graph Overview !

<p>Today, Internet world has enormous data where we need concise and relevant information in least possible steps and time. Graph model of recommendation system is, nowadays, an active field of study and research based on its potential benifits to solve bigger problems in  way sorter time and efficiently give recommendations.</p>

<br>

As we have worked so far,

### User - Movie Metapath

In this, we count the assiciation of one movie to multiple users, if thay rated `(in rating)` the movie, we score the direct assiciation as well as relative association `(weak nodes)`. For direct association, we provide a score (higher than indirect association)`Lets Say 5` and similary find indirect association and provide a score `(less than direct )`, `Lets say 1`for For Example, User 1 and User 2 are similar based on their mutual movie list reviewed and rated. If for a movie M1, if user 1 rated and reviewed the movie, for similarity value, we give a score of 5, meanwhile, User 2 doesn't give any review or rating for M1 but User 2 is similar to user 1 and there is an indirect relaition bewteen User 2 and Movie 1, so here we score 1 for this indirect association.  
