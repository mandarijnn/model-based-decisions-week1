# Model Based Decision Making - Assignment 1: Exploring Real-World Networks

This zip file contains the Jupyter Notebook which analyzes the email communication network from the University Rovira I Virgili in Tarragona dataset and is used for the analysis in the report.
It creates a network graph and computes various network statistics. It also compares the empirical network with three canonical model networks and calculates different centrality measures.

The contents of this zip file can also be found in the following repository: https://github.com/mandarijnn/model-based-decisions-week1/tree/main

## Email communication Database
The database used is the email communication network from the University Rovira I Virgili in Tarragona. The dataset has a dataformat of MTX and can be found at the Network Repository site at: https://networkrepository.com/ia-email-univ.php).

## Required libraries
import pandas as pd
import networkx as nx
import matplotlib.pyplot as plt
import numpy as np
from collections import Counter
import seaborn as sns
from scipy.io import mmread

## Report
The report contains an analysis of the email communication network. It contains:
1. Introduction and Dataset Context
2. Empirical Topological Analysis
3. Model Network Benchmarking
4. Centrality and Node Importance
5. System Dynamics and Policy Implications

## Acknowledgements
The Notebook is based on the example code provided in the Model-Based-Decisions-Code- Week 2 - Networks GitHub
which can be found at: https://github.com/mhlees/Model-Based-Decisions-Code/tree/main/Week%202%20-%20Networks

