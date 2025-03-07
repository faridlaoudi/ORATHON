# Knapsack Problem Solver with Gradio Interface (Orathon 2022)

this is our submission for the Operational research hackathon by Orsc usthb.
This project provides a Python implementation of the **0/1 Knapsack Problem** and integrates it with a **Gradio interface** for interactive use. The knapsack problem is a classic optimization problem where the goal is to select a subset of items with maximum total value, without exceeding a given weight capacity.

## Features
- **Recursive Knapsack Solver**: Implements the 0/1 Knapsack problem using a recursive approach.
- **Gradio Interface**: Provides a user-friendly web interface to input items and weight capacity.
- **Optimal Solution**: Outputs the maximum value, optimal weight, and the best combination of items.

## How It Works
1. **Input**: Users provide a list of items (name, weight, value) and a weight capacity.
2. **Processing**: The program calculates the optimal subset of items using the recursive knapsack algorithm.
3. **Output**: The program returns the maximum value, optimal weight, and the best combination of items.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/knapsack-solver.git
   cd knapsack-solver ```
2. Install the required dependencies
    ```bash
    pip install -r requirements.txt```
3. Usage:
run the jupiter notebook file
    ```bash
    jupiter-notebook knapsack_solver.ipynb ```
