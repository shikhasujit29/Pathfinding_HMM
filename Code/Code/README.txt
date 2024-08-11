This folder contains seven of Jupyter notebooks to illustrate various pathfinding algorithms. Below is an overview of each file and the simulations and visualisations they contain.

Notebooks:
1. Generative model.ipynb
Description: This notebook includes code and visualisations for a generative model applied to a 4x5 grid. It demonstrates how the model generates data based on specified parameters.

2. HMM.ipynb
Description: Implements a Hidden Markov Model (HMM) with only Vertex costs on a 4x5 grid. The visualisations of single, multiple (x20), and optimal paths as determined by the model.

3. HMM – with Edge costs.ipynb
Description: Expanding on the previous HMM implementation by incorporating both Edge Costs and Vertex Costs on a 4x5 grid. The visualisations of single, multiple (x20), and optimal paths.

4. Large Scale.ipynb
Description: This applies an HMM with Edge Costs and Vertex Costs to a uniform hexagonal grid. It includes visualisations and analysis of paths (single, multiple x20, optimal) and reports the total costs after 50 and 250 iterations of the model.

5. Randomly distorted grid.ipynb
Description: Applying HMM on a randomly distorted hexagonal grid, for both Edge and Vertex Costs. Visualisations include single, multiple (x20), and optimal paths, with total costs calculated after 50, 250, and 500 iterations.

6. A star.ipynb
Description: Compares the methods used in the previous notebooks against the A* pathfinding algorithm. It shows the paths found and the total costs associated with these paths.

7. OSM Test.ipynb
Description: Applying the HMM code on an OpenStreetMap to show how it can applied in real-world scenario. Routes produced by three networks have been tested and visualised - walking, driving and biking

To execute the notebooks:
Launch Jupyter and open the notebook of your choice. Execute all the cells within the notebook to run the code. 

**Note** 
The processing time for the "Large Scale" and "Randomly Distorted Grid" notebooks may be longer than others, especially when performing for 250 or 500 iterations.

In the OSM file, three networks have been run separately at different times to show the routes and have been commented out. So uncomment the required network and then run the route code to display the route.