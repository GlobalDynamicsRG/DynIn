# DynIn
Matlab Toolbox for estimating the local integrity measure (LIM) of dynamical systems.

DynIn is a Matlab toolbox that enables computation of the LIM of a dynamical system's steady-state solution (equilibrium or periodic solution). 
Dynamical integrity measures are quantitative measures of the robustness of a stable steady-state against external perturbation. They are usually obtained by computing the basins of attraction of the system; however, this is a very lengthy procedure.
The LIM is a specific dynamical integrity measure defined as the radius of the largest hypersphere entirely included in a steady-state solution's basin of attraction and centered in the solution.
This algorithm can rapidly compute the LIM of a solution without requiring computing the full basin of attraction.

Various examples are provided for utilizing the code.

Please read the tutorial file for an extended explanation of what the code can be used for, how to install it, its limitations, and so on.  
[Tutorial_v1.0.1.pdf](https://github.com/GiuseppeHabib/DynIn/files/10426931/Tutorial_v1.0.1.pdf)

Please note that this is a beta version, and we plan to extend the code significantly. Our objective is to create a toolbox with several functions to analyze the global behavior of dynamical systems.

Extensive discussion and contextualization of the algorithm concerning the current scientific literature are available in this paper  
[ND - Dynamical integrity assessment of stable equilibria a new rapid iterative procedure (2021).pdf](https://github.com/GiuseppeHabib/DynIn/files/10426939/ND.-.Dynamical.integrity.assessment.of.stable.equilibria.a.new.rapid.iterative.procedure.2021.pdf)  
Please cite this paper if you use this code for your scientific research.
