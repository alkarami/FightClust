# FightClust
Repository for the creation of a fighter odds matrix, as well as the clustering steps for downstream analysis. Clustering will be based 
on the fighters each fighter has won and lost against.

*Roster Selection*

It's probably a good idea to keep the matrix populated by fighters of the same era, or fighting in the same promotions/circuits.
This ensures that the fights have some relevance to each other. For example, we wouldn't want to include both golden era fighters 
and modern american fighters, because these people wouldn't be fighting anyone in common. One way to curate a custom list of fighters 
is using Wikipedia books: https://en.wikipedia.org/wiki/Help:Books#Step-by-step_guide. Select a custom list of fighters, then their
fight records table can be easily scraped after downloading. 

*Odds Matrix* 

The design of the odds matrix will be based on an identity matrix. Both rows and columns will feature *names* of fighters.
The intersection of the matrix is then defined as the number of times the fighter in the *row* defeats the fighter in the *column*.
The intersection between the same fighter will have a value of 0. 

*Clustering* 

The idea is to identify groups of identical fighters, given who they won and lost against. Inferences can then be made after
groups are identified, based on commonalities shared between the groups: Are these tall fighters? Do they share a common geography? 

