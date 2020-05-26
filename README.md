# FightClust
Repository for the creation of a fighter odds matrix, as well as the clustering steps for downstream analysis.

*Odds Matrix* 
The design of the odds matrix will be based on an identity matrix. Both rows and columns will feature *names* of fighters.
The intersection of the matrix is then defined as the number of times the fighter in the *row* defeats the fighter in the *column*.
The intersection between the same fighter will have a value of 0. 

*Clustering* 
The idea is to identify groups of identical fighters, given who they won and lost against. Inferences can then be made after
groups are identified, based on commonalities shared between the groups: Are these tall fighters? Do they share a common geography? 

