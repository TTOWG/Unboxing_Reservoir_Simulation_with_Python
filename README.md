# Unboxing_Reservoir_Simulation_with_Python
 A Pedagogical Unboxing of Reservoir Simulation with Python
   
Reservoir simulation, being a state-of-the-art tool for reservoir performance prediction, is an essential part of the petroleum engineering undergraduate and post-graduate curricula. While the science of reservoir simulation (governing models and solutions) is considered well-taught in academic programs, companies train their reservoir engineering staff on the art of using a simulation software. However, not much teaching attention has been given to the coding of the governing models and solutions to make the softwares. Yet, the coding is unarguably the link between the science and the art.  Regrettably, this missing link has made reservoir simulation appear like a black-box to students. This project therefore sets out to unbox reservoir simulation by presenting an interactive Python script that completely implements the workflow of a simple 3D single-phase oil reservoir simulator. The Python script contains code chunks, explanatory texts and visual objects.
  
#### Project Outline
1	Reservoir Simulator Workflow - presentation of major workflow steps
2	Input Data File
 ●	Data preparation with the .csv template
 ●	Data importation from .csv into Python as DataFrame
 ●	DataFrame formatting
3	Reservoir Discretization and Visualization
 ●	Computation of gridblock dimensions
 ●	Generation of gridblock ordering data
 ●	3D visualization of discretized model
●	Gridblock categorization
⮚	Stating the need for categorization
⮚	Establishing the basis of categorization
⮚	Scripting categorization functions
●	Visualization of gridblock categories
⮚	Static color-coded graphics using matplotlib
⮚	Dynamic interactive plots – using plotly

4.	Simulation Parameter Computations
●	Gridblock cross-sectional area, in x, y, z directions
●	Gridblock bulk volume, in ft3 and bbl.
●	Reservoir STOIIP
●	Gridblock STOIIP
●	Effective compressibility
●	Inter-block flow transmissibilities, in x, y, z directions
●	Setting flow model coefficients

5.	Gridblock-Level Modelling
●	Simulation loops through the discretized model: variables and counters
●	Programmatically-convenient presentation of the governing equation
●	Loop flowchart
●	Indices of the current block
●	Indices of the neighbouring blocks:
i.	Formulating the algorithm
ii.	Scripting the function
●	Implementation of boundary condition
●	The Coefficient matrix
●	Well-blocks identification and modelling
●	The RHS vector
●	Block pressures matrix

6.	Volumetric Computations
●	The MBE model
●	Computation flowchart
●	PVT Updating
●	Performance prediction

7.	Loop termination mechanism

8.	Output Aggregation and Export
  
