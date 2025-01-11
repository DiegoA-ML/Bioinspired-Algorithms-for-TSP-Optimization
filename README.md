# Bioinspired-Algorithms-for-TSP-Optimization

In this project, we employed bioinspired algorithms to solve the classic Traveling Salesman Problem (TSP) and compared their performance to an exact optimization model. The TSP is an NP-hard problem where the objective is to find the shortest possible route visiting all nodes exactly once. We focused on networks ranging from 40 to 200 nodes.

## Key Techniques and Results:
 
 1 Genetic Algorithm (GA): We modeled evolution by using selection, crossover, and mutation to iteratively improve the solution. By mimicking natural selection, the GA explored multiple paths and converged on optimal or near-optimal solutions. The GA found a best path of 407.27 km for the 40-node network, with a computation time of 4.84 seconds.
 
 2 Ant Colony Optimization (ACO): Inspired by the behavior of ants, this algorithm simulates pheromone trails to find efficient routes. It achieved a highly accurate result for the 40-node network, covering a path of 162.94 km in just 2.72 seconds.
 
 3 Exact Model (GAMS): Using traditional optimization methods, we solved the TSP exactly for comparison. The GAMS model achieved a shortest path of 151.34 km for the same network with a computation time of 1.58 seconds.

## Performance Insights:

 • The genetic algorithm reached 35.88% fitness of the exact solution in significantly more time. We can assume we made mistakes as this is unlike Genetic Algorithms. We look forward to fixing them.
 
 • The ant colony algorithm demonstrated 92.05% fitness with far quicker computation, showing its strength in approximating solutions rapidly.

 • For larger networks (100, 150, and 200 nodes), the bioinspired algorithms demonstrated their scalability and efficiency.

This project showcases the power of bioinspired computation to tackle real-world optimization problems, highlighting the potential of algorithms modeled after natural phenomena.

Skills: Optimization · Genetic Algorithms · Optimization Algorithms · Python (Programming Language) · GAMS
