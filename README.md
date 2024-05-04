# TravellingSalesmanProblem-GeneticAlgo-GUI

Python program that uses genetic algorithms to solve the classic Travelling Salesman Problem (TSP). The TSP is a combinatorial optimization problem where the goal is to find the shortest possible route that visits each city exactly once and returns to the origin city.

Small program to solve TSP using Genetic Algorithm.
first it solves by bruteforce

# Features

- Uses a genetic algorithm approach to find near-optimal solutions to the TSP.
- Supports customization of population size, mutation rate, and termination criteria.
- Provides visualization of the best route found and convergence over generations.

## Genetic Algorithm

The genetic algorithm used in this project follows these steps:

1. **Initialization**: Generate an initial population of candidate solutions randomly.
2. **Evaluation**: Evaluate the fitness of each candidate solution (route) based on its total distance.
3. **Selection**: Select the most fit individuals (routes) to proceed to the next generation.
4. **Crossover**: Create new candidate solutions (offspring) by combining genetic material from selected individuals.
5. **Mutation**: Introduce random changes (mutations) to the offspring to maintain genetic diversity.
6. **Replacement**: Replace the least fit individuals in the population with the new offspring.
7. **Termination**: Repeat the process until a termination condition is met (e.g., maximum number of generations or convergence).

## Usage

To run the genetic algorithm with default settings, simply execute the script:

`python3 tspbrute.py `

secondly we are useing Genetic Algo

` python3 tspga.py `
