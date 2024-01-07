# Topology of Bayesian Belief-Networks
Project for Advanced Statistics for Physics Analysis at University of Padova 2023.
A Bayesian belief-network [[1]](#ref1) structure is a directed acyclic graph in which nodes represent domain variables
and arcs between nodes represent probabilistic dependencies [[2]](#ref2).
Given a database of records, it is interesting to construct a probabilistic network which can provide insights
into probabilistic dependencies existing among the variables in the database. Such network can be further used
to classify future behaviour of the modelled system [[2]](#ref2).

Although researchers have made substantial advances in developing the theory and application of belief networks,
the actual construction of these networks often remains a difficult, time consuming task. An efficient method for
determining the relative probabilities of different belief-network structures, given a database of cases and a set
of explicit assumptions is represented by the K2 algorithm [[2]](#ref2)[[3]](#ref3).

In this project after having studied the problem in the literature ([ [2] ](#ref2)-[[3]](#ref3)), I implement in R the algorithm and
check its performances on datasets progressively more complexed: CH93 [ [3] ](#ref3), Asia and Child datasets [ [6] ](#ref6).
Finally i compare these results with those obtained with the library "bnstruct". 





## **BIBLIOGRAPHY**

<a id='ref1'></a>
**[1]** M. Scutari and J. B. Denis, *Bayesian Networks*, CRC Press, 2022, Taylor and Francis Group

<a id='ref2'></a>
**[2]** G. F. Cooper and E. Herskovits, *A Bayesian Method for the Induction of Probabilistic Networks from Data*, Machine Learning 9, (1992) 309

<a id='ref3'></a>
**[3]** C. Ruiz, *Illustration of the K2 Algorithm for learning Bayes Net Structures*, http://web.cs.wpi.edu/~cs539/s11/Projects/k2_algorithm.pdf


<a id='ref4'></a>
**[4]** A. Franzin et al., *$\texttt{bnstruct}$: an R package for Bayesian Network structure learning in the presence of missing data*, Bioinformatics 33(8) (2017) 1250

<a id='ref5'></a>
**[5]** F. Sambo and A. Franzin, *$\texttt{bnstruct}$: an R package for Bayesian Network Structure Learning with missing data*, December 12, 2016

<a id='ref6'></a>
**[6]** https://www.bnlearn.com/bnrepository/
