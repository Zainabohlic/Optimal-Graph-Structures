# Optimal Graph Structure

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
- **sourceCode.ipynb**: Contains the main code for reading input data, constructing the graph, and applying search algorithms.
- **datasets**: Contains input datasets for experimentation.

## Usage
#### Running IPython Notebook on Conda

To run an IPython Notebook (`.ipynb` file) on Conda, follow these steps:

1. **Activate Conda Environment:** Open your terminal or command prompt and activate your Conda environment where you have installed Jupyter Notebook:

    `conda activate (enviornment name)`

   Replace `(environment name)` with the name of your Conda environment.

3. **Install Jupyter Notebook (if not installed):** If you haven't installed Jupyter Notebook in your Conda environment, you can install it using the following command:

   `conda install jupyter`
   
5. **Navigate to Notebook Directory:** Use the `cd` command to navigate to the directory where your `.ipynb` file is located.

6. **Launch Jupyter Notebook:** Once you are in the directory containing your notebook file, run the following command to launch Jupyter Notebook:

    `jupyter notebook`
   
8. **Access Notebook in Browser:** After running the above command, Jupyter Notebook will open in your default web browser. You should see a file browser interface where you can navigate to your `.ipynb` file. Click on the file to open and run it.

9. **Run Notebook Cells:** Once the notebook is open, you can run each cell individually by selecting it and pressing `Shift + Enter`. Alternatively, you can run all cells by selecting `Cell` from the menu and choosing `Run All`.

