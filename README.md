# Traveling Salesman Problem (TSP) Solver using Genetic Algorithm 🧬🗺️

This project provides a solution to the classical **Traveling Salesman Problem (TSP)** using a **Genetic Algorithm** (GA) approach. The TSP involves finding the shortest possible route that visits a set of cities exactly once and returns to the origin city.

## 🚀 Features

- Initializes a random population of possible routes.
- Applies **Genetic Algorithm techniques**:
  - **Selection**: Choosing the best candidates.
  - **Crossover**: Combining parts of two routes.
  - **Mutation**: Randomly changing parts of routes to explore new solutions.
- Calculates total distances using **Euclidean distance**.
- Visualizes:
  - City coordinates
  - Evolution of the best route
  - Comparison charts with seaborn
- Optimized for readability and performance with NumPy and matplotlib.

## 📁 File Structure

- `TSP_GA.ipynb`: Jupyter Notebook containing the full code, comments, and plots.
- `README.md`: Project overview and instructions (this file).

## 🧠 How It Works

1. **Generate cities**: A list of city coordinates is created.
2. **Initial population**: Multiple random routes (permutations of cities) are generated.
3. **Fitness evaluation**: The total distance of each route is calculated.
4. **Genetic operations**:
   - Fittest routes are selected.
   - New routes are created via crossover and mutation.
5. **Termination**: The algorithm runs for a fixed number of generations or until convergence.
6. **Visualization**: The shortest path found is displayed with plotted city connections.

## 📦 Dependencies

- Python 3.x
- NumPy
- Matplotlib
- Seaborn
- Pandas

You can install the required libraries using:

```bash
pip install numpy matplotlib seaborn pandas
