# Workshop: Using PLUMED to enhance sampling in Gromacs

## Description
- We will outline basic methods of working with PLUMED.
- Duration: 90 minutes
- Objectives: be able to 
    - Setup simulations using PLUMED+GROMACS
    - Define collective variables
    - Setup various types of biased simulations
    - Perform steered MD
    - Perform Metadynamics simulations
    


## Jupyter notebooks
- We follow [this tutorial](https://github.com/intbio/MolModEdu/tree/master/PLUMED) but use updated files.
- [plumed_intro.ipynb](plumed_intro.ipynb)
- [plumed_bias.ipynb](plumed_bias.ipynb)
- [plumed_metad_intro.ipynb](plumed_metad_intro.ipynb)



## Required software and resources
- Create NEW conda environment with Python 3.7 and install Gromacs+PLUMED in it using “conda install -c conda-forge -c intbio gromacs=2018.4_plumed_2.5.0” command
- Install MDAnalysis and nglview libraries in this conda environment.


## Learning resources
- [A quick introduction to PLUMED](https://www.youtube.com/watch?v=PxJP16qNCYs)
- [Video lecture on MetaDynamics](https://www.youtube.com/watch?v=bZZggbV2r5E)
- [PLUMED manual](https://plumed.github.io/doc-v2.3/user-doc/html/_syntax.html) 



## Assignments

Take an arbitrary alpha-helix from your protein of interest with length of up to 10 aminoacids:
1. Run MD where the ends of this helix will be stretched with a restraint.
2. Present MD snapshots.
3. Plot of distance between the end C-alpha atoms of the helix with time.

Take the first two amino acids from this helix (a dipeptide).
1. Run  unbiased simulations of the dipeptide.
2. Plot a Ramachandran plot the the phi and psi angles.
3. Perform Metadynamics simulations by biasing phi and psi angles.
4. Make a comparative Ramachandran plot for the two simulations.

(*) Take an arbitrary alpha-helix from your protein of interest with length of up to 10 aminoacids:
1. Run steered MD where the ends of this helix will be gradually stretched with a [moving restraint](https://www.plumed.org/doc-v2.5/user-doc/html/_m_o_v_i_n_g_r_e_s_t_r_a_i_n_t.html).
2. Present MD snapshots.
3. Plot of distance between the end C-alpha atoms of the helix with time.


### Troubleshooting
- Consult with the seminar protocol/recording
- Ask questions in Telegram
