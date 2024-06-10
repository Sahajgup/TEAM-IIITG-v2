# PACE2024
This solver converts the OSCM problem into an Integer Linear Programming Optimization problem. We use CBC solver to solve the ILP. We apply a few optimmizations as preprocessing steps before passing it on to the solver along with constraints and an objective to minimize the number of crossings.

# Requirements
This solver requires ortools library.

# Build and Run
Install Python3 (https://www.python.org/downloads/)
Install Pip (https://pip.pypa.io/en/stable/installation/)
Install libraries : pip install -r requirements.txt
Run the solver : python3 solution-2.py < input.gr
