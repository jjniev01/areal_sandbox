# Overview
This repository contains a single file, namely the code notebook containing the code used to carry out all of the processing in the paper: 

Nieves, J. J., Gaughan, A. E., Stevens, F. R., Yetman, G, &  A. Gros. Under Reivew. "A simulated 'sandbox' for exploring the modifiable areal unit problem in aggregation and disaggregation". Nature Scientific Data.

This notebook also contains an accompanying explanation/narrative of the purpose of the code along with some accessory descriptive figures of the input areal population data. 

The notebook is contains the following major sections along with sub sections. The main sections are self explanatory in their names, but I provide a brief description of their subsections here.

* Data and Study Areas
  - Spatial Population Data Preprocessing: Description and code of how we took the data from the Mexican Census to the inital data that we worked with in the simulations.
  - Input Areal Population Data Descriptives: A section giving descriptive information about the areal and population attributes of the areal-based census data we input in to the simulations.

* Methods
  - Census Simulation: Brief descriptive overview of the goals and architecture of the methods
  - Polygon Simulation - Single Simulation: Description of the code of how we produced a single simulation run.
  - Polygon Simulation - Task Farm: Description of the larger task farm that allowed us to run multiple simulations in parallel on a given node.
  - Polygon Simulation - Job List: Description of the job list that was used to submit batches or job arrays, of the task farm of simulations, to the HPC.
  - Polygon Simulation - Job Submission Script: Description of the script used to submit the jobs to the HPC, in conjunction with the Job List.

* Appendix A - Utility Functions: These are custom functions that are called within the main blocks of code, but are not defined within them and are placed in this section for clearer reading and separation of custom functionality that is not the main purpose of that block.
