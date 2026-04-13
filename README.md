Algorithm Comparison

| Algorithm | Strategy | Time Complexity | Space Complexity | Advantages | Limitations |
|----------|---------|----------------|------------------|-----------|------------|
| Merge Sort | Divide & Conquer | O(n log n) | O(n) | Efficient for large data, stable | Requires extra memory |
| Bubble Sort | Brute Force | O(n²) | O(1) | Simple to understand | Very slow for large inputs |
| Fractional Knapsack | Greedy | O(n log n) | O(1) | Fast, optimal for fractional cases | Not suitable for 0/1 problems |
| 0/1 Knapsack | Dynamic Programming | O(n × W) | O(n × W) | Gives optimal solution | High memory usage |


In real-world systems, decision-making and optimization problems arise in domains such as logistics, finance, healthcare, and e-commerce. Problems like route optimization, resource allocation, scheduling, and data processing require efficient algorithmic solutions.

Different algorithmic paradigms are used depending on the nature of the problem:
- Divide and Conquer for sorting and large-scale processing
- Greedy Algorithms for local optimization problems
- Dynamic Programming for problems with overlapping subproblems

This project implements and compares these strategies to understand their efficiency and practical applicability.


Learning Objectives
- Implement algorithms using Divide and Conquer, Greedy, and Dynamic Programming
- Analyze performance using execution time
- Visualize performance using graphs
- Understand scalability and efficiency of different algorithms
- Write clean and modular code

Algorithms Implemented

Problem 1: Divide and Conquer
- Merge Sort
- Performance measured for different input sizes
- Time vs Input Size graph plotted

Problem 2: Sorting Performance Comparison
- Bubble Sort vs Merge Sort
- Execution time comparison
- Graph visualization showing efficiency difference

Problem 3: Greedy Algorithm
- Fractional Knapsack
- Maximizes profit using value-to-weight ratio
- Outputs selected items and total value

Problem 4: Dynamic Programming
- 0/1 Knapsack
- Uses DP table to store subproblem results
- Execution time measured and optimal value computed

Performance Analysis
- Execution time measured using Python `time` module
- Graphs plotted using `matplotlib`
- Comparison shows:
  - Merge Sort is significantly faster than Bubble Sort
  - Greedy works efficiently for fractional problems
  - Dynamic Programming ensures optimal solutions

Tools & Technologies
- Python 3
- Jupyter Notebook 
- Libraries:
  - matplotlib
  - random
  - time

How to Run
1. Open the notebook using Jupyter Notebook
2. Run all cells sequentially
3. Observe outputs, execution times, and graphs
