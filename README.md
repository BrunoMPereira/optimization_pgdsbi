# Knapsack Problem Optimization using Genetic Algorithm

## Overview
This project implements an optimization of the **Knapsack Problem** using a **Genetic Algorithm (GA)**. The approach is inspired by [Arpit Bhayani’s blog](https://arpitbhayani.me/blogs/genetic-knapsack/) and lessons from an **Optimization class** in a **Post-Graduate Program in Data Science and Business Intelligence**.

README.md was built using ChatGPT. The rest of the work was done based only on the code learned from the classes and the example given above.

## Problem Statement
The **Knapsack Problem** is a common optimization challenge where we aim to maximize the value of items placed in a knapsack while staying within a weight limit.

## Solution Approach
A **Genetic Algorithm (GA)** is used to find a good solution efficiently.

### Steps of the Genetic Algorithm
1. **Initialization**: Create a random population of potential solutions.
2. **Fitness Evaluation**: Assess solutions based on their total value while staying within the weight limit.
3. **Selection**: Pick the best solutions to create the next generation.
4. **Crossover**: Combine parts of two solutions to create new ones.
5. **Mutation**: Introduce small changes to maintain diversity.
6. **Iteration**: Repeat the process until a good solution is found.

## Key Features
- **Adjustable Parameters**: Customize population size, mutation rate, and crossover probability.
- **Selection Strategies**: Implemented **Tournament Selection**.
- **Crossover and Mutation**: Ensures diversity in solutions.

## References
1. [Arpit Bhayani’s Blog](https://arpitbhayani.me/blogs/genetic-knapsack/)
2. Post-Graduate Optimization Class Notes

## Author
Bruno Miguel Marques Pereira

