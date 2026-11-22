# Model Based Decision Making - Assignment 2: Dynamics on Networks: Thresholds and Spreading

This zip file contains the Jupyter Notebook used to simulate a Granovetter-style threshold contagion on the email communication network used in assignment 1. 

The contents of this zip file can also be found in the following repository: https://github.com/mandarijnn/model-based-decisions-week1/tree/main

## Email communication Database
The database used is the email communication network from the University Rovira I Virgili in Tarragona. The dataset has a dataformat of MTX and can be found at the Network Repository site at: https://networkrepository.com/ia-email-univ.php.

## Required libraries
import ipywidgets as widgets
import numpy as np
import pandas as pd
import networkx as nx
import matplotlib.pyplot as plt
import random
from time import time
import os
from scipy.io import mmread

## Report
The report contains an analysis of the email communication network. It contains the following sections:
1. Model Setup & Network Summary
2. Experimental Setup
3. Seeding Strategy Comparison
4. Sensitivity Analysis & Tipping Points
5. Topological Discussion & Policy Recommendations

## Acknowledgements
The Notebook is based on the example code provided in the Model-Based-Decisions-Code- Week 3 - Dynamics on Networks GitHub
which can be found at: https://github.com/mhlees/Model-Based-Decisions-Code/tree/main/Week%203%20-%20Dynamics%20on%20Networks