# Vertex Ordering Problem Solver

## Overview
This Python project implements search algorithms (BFS, DFS, UCS) to solve an optimization problem known as the vertex ordering problem. The goal is to find an optimal ordering of vertices in a graph structure, considering associated costs of parent sets for each vertex. This problem has applications in various fields, including machine learning (e.g., Bayesian Network Learning).

## Problem Description
Given a set of vertices V1, ..., Vn and possible parent sets for each vertex with associated costs, the task is to find an ordering of vertices O that minimizes the total cost of the network. A parent set of a vertex Vi is consistent with an ordering O if all of the parents come before the vertex in the ordering.

## Implementation
The project provides implementations of three search algorithms:
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)

### Input Data Format
The input data represents vertices and their possible parent sets along with associated costs. Each dataset includes examples to experiment with.

### Functionality
- Each search algorithm is implemented as a separate function.
- The program reads input data, constructs the graph, and applies search algorithms to find the minimum cost ordering of variables.
- The minimum cost ordering and its cost are printed as output.

## Evaluation
Three datasets are provided for experimentation. The project evaluates the search algorithms on these datasets to determine their effectiveness in finding optimal solutions.

## Project Structure
- **sourceCode.py**: Contains the main code for reading input data, constructing the graph, and applying search algorithms.
- **datasets/**: Contains input datasets for experimentation.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Ensure Python 3.x is installed on your system.
4. Run the following command to execute the program:
   ```bash
   python SourceCode.py
