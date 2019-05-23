# route-optimiser

## What is it?

This is a route optimizer to find the best way to get around the University of Auckland buildings. This is a machine learning algorithm, specifically a genetic algorithm.

This genetic algorithm creates 100 random routes initially (called 1 generation) and uses Darwins principles of evolution to evolve from generation to generation by mixing and matching different parts of the good routes to try make better ones.

## Implementation

This is written in python using a jupyter notebook. Each building is represented as a tuple of coordinates. I used a library called [geopy](https://pypi.org/project/geopy/) which calculates the distance between 2 coordinate points.

The base of this code was taken from [towards science](https://towardsdatascience.com/evolution-of-a-salesman-a-complete-genetic-algorithm-tutorial-for-python-6fe5d2b3ca35) and altered to make the implementation more relevant to my situation.

## Learnings

- I learnt about genetic algorithms. I learnt about how they work and what makes them unique.
- I used Jupyter Notebook for the first time. It was interesting to learn a new tool for rapid development.
