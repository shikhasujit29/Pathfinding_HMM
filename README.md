**Exploring Pathfinding Solutions through Probabilistic Means: Customizing Hidden Markov Model Framework**

**Overview**

This project investigates pathfinding solutions through probabilistic approaches by customizing the Hidden Markov Model (HMM) framework. Traditional pathfinding algorithms like Dijkstra’s and A* rely heavily on deterministic approaches, which often struggle in dynamic and uncertain environments. This research introduces a probabilistic dimension to pathfinding, leveraging HMMs to explore multiple near-optimal paths rather than converging on a single solution.

The study demonstrates the application of HMMs in grid-based and hexagonal layouts, optimizing the transition matrix using the Expectation-Maximization (EM) algorithm. The project compares the results of the HMM-based approach with the traditional A* algorithm, highlighting the benefits of incorporating probabilistic models in complex navigation tasks.

**Key Findings**

1. Generative Model:

 - Initial experiments using a generative model showed that HMMs could handle uncertainty by producing random walks across the grid.
 - Optimization refined these paths, directing them toward the goal state while minimizing costs.

2. Optimized Model (Vertex & Edge Costs):

 - The project explored two optimization scenarios: one focusing on vertex costs and the other on edge costs.
 - The HMM-based approach demonstrated superior performance in environments where costs are dynamically adjusted, proving its robustness in avoiding high-cost areas.

3.Larger Scale Implementations:

 - The application of HMMs on more complex grids, including hexagonal layouts with random perturbations, showcased the model’s scalability and adaptability.
 - The introduction of Gaussian Mixture Models (GMMs) to determine vertex costs further enhanced the model’s effectiveness.

4.Comparison with A*:

 - While the A* algorithm efficiently identified the shortest paths, it occasionally selected routes through high-cost areas.
 - In contrast, the HMM framework consistently avoided such paths, reinforcing its advantage in handling uncertainties and providing multiple near-optimal solutions.


**Conclusion**

The research concludes that HMMs offer a powerful alternative to traditional pathfinding algorithms, especially in environments characterized by uncertainty and dynamic changes. The ability of HMMs to generate multiple near-optimal paths makes them highly suitable for real-world applications, where flexibility and adaptability are crucial.
