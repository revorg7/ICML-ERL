# ICML-ERL
This repository provides link to the code of our workshop submission at ICML-2018. The code is implemented as a part of larger RL library maintanied by our group. Here you can find my fork which implementes the "Deeper & Sparser Sampling" paper published at the Exploration in Reinforcement Learning Workshop at the 35th International Conference on Machine Learning.

The repository link for the code is https://github.com/revorg7/beliefbox. The relevant files are:
1. TreeBRLPolicy.h/cc containing the sparser tree code. You can find other benchmark algorithms implemented in TreeBRL.h/cc
2. test_tree_brl_policy.cc which calls the TreeBRLPolicy class and tests it on various environments.

The plotter.ipynb file added in this repository can parse the output printed out by compiled binary of test_tree_brl_policy.


