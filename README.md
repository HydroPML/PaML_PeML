# Physics-embedded Machine Learning
PeML is achieved by embedding physics in the model frameworks or modules. It can be divided into physical equation-embedded ML (PEeML), physical property-embedded ML (PPeML), and physical condition-embedded ML (PCeML). 
# Physical Equation-embedded Machine Learning
![image](https://github.com/HydroPML/PaML_PeML/blob/main/Table5.png)
# Physical Property-embedded Machine Learning
Physical properties usually include symmetry and conservation of physical systems. By building a neural network that inherently respects a given physical property, we thus make conservation of the associated quantity more likely and consequently the model’s prediction more physically accurate. 
# Physical Condition-embedded Machine Learning
There are many physical conditions in the physical system, such as boundary conditions and initial conditions in PDEs, boundaries of land use and land cover in the physical environment, and so on. Violating these conditions can lead to unstable models and non-physical solutions. Thus, it is critical for ML to satisfy these constraints in order to capture the underlying physics accurately and provide reliable models for rigorous research and engineering design. Specifically, for PDEs, three types of boundary conditions (BCs) that are widely used to model physical phenomena are (1) Dirichlet: fixed-value at the boundary; (2) Neumann: fixed-derivative at the boundary; and (3) periodic: equal values at the boundary.  
**Continuously updating**   
More information can be found in the [PAPER](https://arxiv.org/abs/2310.05227)  

