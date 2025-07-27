# Genetic Algorithm for Smart Grid Energy Optimization

## Project Overview
This repository implements a parallel Genetic Algorithm (GA) to solve constrained optimization problems in smart grid energy distribution. The algorithm minimizes operational costs while satisfying demand and adhering to capacity constraints.

## Key Components
- **Chromosome Encoding**: Custom chromosome encoding for 3D energy allocation, 3D matrix representation (Sources × Nodes × Time)
- **Fitness Function**: Combines cost, transmission loss, and constraint penalties
- **Parallelization**: Multiprocessing for fitness evaluation
- **Constraint Handling**: Adaptive penalty system for:
  - Demand fulfillment
  - Source capacity limits
  - Peak-hour restrictions
-  Performance comparison with greedy baseline
-  Convergence visualization tools
  

## Installation
```bash
git clone https://github.com/RoojMaharjan/Genetic-Algorithm.git
cd Genetic-Algorithm
pip install -r requirements.txt
