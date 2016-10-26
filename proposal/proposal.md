Title: Intelligent Systems, Group 9 Project Proposal
Author: Cameron Reid
Author: [your name here]
Author: [your name also here]

[TITLE]

# Motivation

We formulated two questions during our learning to this point: What would a
Bayes network look like if the DAG constraint were loosened to allow
undirected and possibly cyclical graphs? Further, we wondered if there were a
way to resolve the absolute nature of first order logic with the uncertainty of
real-world problems.

In our exploration related to these questions, we came across a 2006
publication by Richardson and Domingos which describes the notion of a Markov
logic network. MLNs expand the idea of Markov random fields with first-order
logic to provide a way to model knowledge in ways that a Bayesian network
cannot.

# Proposal

We would like to implement and test a MLN against the "Heart Disease" data set
from UCI (found here: http://archive.ics.uci.edu/ml/datasets/Heart+Disease). We
would like to compare the results of that implementation against other more
standard methods, such as a decision tree and a Bayesian network, to provide
perspective into how well the model performs.

It is our hope that during the research and implementation of the MLN, we will
achieve better insight about these kinds of models, and that insight will lead
to a novel alteration to the model or implementation detail that would be
worthy of note.
