# Sudoku Solver (CSP Optimization)

## 📌 Project Description
A high-performance Sudoku solver implemented in C++ using Constraint Satisfaction Problem (CSP) techniques. The project focuses on optimizing brute-force search algorithms through intelligent heuristics.

## 🧠 Core Features
* **CSP Approach:** Models Sudoku as a set of variables, domains, and constraints (no duplicates in rows, columns, or 3x3 grids).
* **MRV Heuristic:** Implements the "Minimum Remaining Values" strategy—prioritizing cells with the fewest valid options to prune the search tree early.
* **Efficient Pruning:** Dynamically updates domains of related cells after each move, drastically reducing the search space compared to standard backtracking.
