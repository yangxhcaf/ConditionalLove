# ConditionalLove

This repository contains the code and data to reproduce the analysis described in:
de Jonge, M. M. J., Benítez-López, A., Hennekens, S., Santini, L., Huijbregts, M. A. J. & Schipper, A. M. <i>Contitional love? Evidence for the stress gradient hypothesis in dry grasslands across Euope.</i> 

Code and data needed to reproduce the pre-processing steps are not made available due to restrictions on publication of third party data. 

The following steps should be taken to replicate the Joint-SDMs described in the paper: 

Step 1: Run the main model in MATLAB using run_model(1,800,250,10,3). You can also run the static model with run_static_model(1,800,250,3). WARNING: This step may take a long time, in the order weeks. 

Step 2: Check the convergence the beta parameters of the model using check_convergence('Conditional',1,1)

Step 3: If the models are converged combine the postiors of the runs and discard the burnin period using finalize_model()

To replicate the analysis of the model:


This repository includes the HMSC package V2.1 for MATLAB which can be found at: https://www.helsinki.fi/en/researchgroups/statistical-ecology/software/old-versions-of-hmsc

 
