# MCMCforPDEs
Numerical resolution of a few PDEs using Markov Chains.
We cover three differential equations with Dirichlet boundary conditions:
* Equation 1 (Laplace equation): ![equation](https://latex.codecogs.com/gif.latex?%5CDelta%20f%28x%2Cy%29%20%3D%200)
* Equation 2: ![equation](https://latex.codecogs.com/gif.latex?%5CDelta%20f%28x%2Cy%29%20-%20%5Cgamma%20f%28x%2Cy%29%20%3D%200)
* Equation 3: ![equation](https://latex.codecogs.com/gif.latex?%5CDelta%20f%28x%2Cy%29%20-%202f%28x%2Cy%29%20&plus;%20f%28x%2Cy%29%5E2%3D%200)

For the second equation, we suggest two different methods (`cemetery` and `Feynman-Kac`). For each method we include three Jupyter notebooks:
* The first (`proof`) contains a description of the method and a proof that it provides a good approximation of the equation's solution.
* The second (`edge_reached`) contains the code computing and plotting an approximation of the solution.
* The third (`evolution`) contains the code computing and plotting an approximation of the evolution of the associated time-dependent equation (*e.g.* the Heat equation for the Laplace equation).