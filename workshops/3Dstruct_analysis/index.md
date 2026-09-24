# Workshop: Analyzing 3D PDB structures.

## Description
- Complex analysis of PDB structures
- Duration: 90 minutes
- Objectives: be able to 
    - do analysis in Python using MDanalysis and Prody libraries
    - select, extract and analyze atom coordinates and dihedral angles.
    - add hydrogens to the structure
    - identify hydrogen bonds
    - identify protonation states
    - assign charges to the atoms
    - compute and analyze electrostatic surface
    - build contact maps
    - identify domains
    - analyze dynamics using elastic networks models

## Jupyter notebook
- [3Dstruct_analysis.ipynb](3Dstruct_analysis.ipynb)
## Required software and resources
- UCSF Chimera (optional)
- Access to a Jupyter notebook environment with Python 3
- 3-button mouse

**List of Conda packages:**
- MDanalysis 
- nglview  
- prody 
- propka or use https://www.ddl.unimi.it/vegaol/propka.htm 
- pdb2pqr or use https://server.poissonboltzmann.org/pdb2pqr
- apbs or use https://server.poissonboltzmann.org/apbs

**Channels list (if you use Anaconda Navigator):**
- conda-forge
- schrodinger 

## Learning resources
- MDanalysis tutorial [https://www.mdanalysis.org/MDAnalysisTutorial/](https://www.mdanalysis.org/MDAnalysisTutorial/)
- Prody tutorial [http://prody.csb.pitt.edu/tutorials/prody_tutorial/](http://prody.csb.pitt.edu/tutorials/prody_tutorial/)
- APBS documentation [https://apbs.readthedocs.io/en/latest/](https://apbs.readthedocs.io/en/latest/)


## Assignments

A  PDB structure of a protein with at least two domains  will be suggested for analysis.
The assignment report should include section detailing the following:

1. Adding hydrogens to the structure
2. Identify hydrogen bonds
3. Protein dihedral angle analysis
4. Contact maps
5. Identify protonation states of ionizable residues
6. Visualize electorstatic potential at the surface using PDB2PQR and APBS

*. Identify domains using SCOPe, PFAM and/or NCNI protein databases
*. Dynamics analysis

### Suggested problem sets
Each student should take a unique PDB structure with at least two domains from the PDB web-site at his/her own discretion.

### Troubleshooting
- Consult with the seminar protocol/recording
- Try to Google, and see Pymol Wiki
- Ask questions in TG
