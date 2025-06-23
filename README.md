# FCP_DIATOMS
Conformational Plasticity Enables Functional Switching in Diatom Light-Harvesting Complexes
Theofani-Iosifina Sousani,1 Boutheina Zender,1 Sayan Maity,2,3 Ulrich Kleinekathöfer,2 and Vangelis Daskalakis*,1

1-Department of Chemical Engineering, University of Patras, Patras 265 04, Greece, 
2-School of Science, Constructor University, 28759 Bremen, Germany,
3-current address: Department of Physics and Astronomy and Thomas Young Centre, University College London, London WC1E 6BT, U.K.
*Corresponding author: Vangelis Daskalakis.

This is the code and training data for classifying FCP structures of diatoms

The work on FCP oligomerization in Ph. tricornutum and Ch. Gracilis is funded by the Hellenic
Foundation for Research & Innovation (H.F.R.I) in the context of the call “Basic Research
Financing (Horizontal support for all Sciences), National Recovery and Resilience Plan
(Greece 2.0) for the project number 014775, with acronym “SUNDIAL”.
This project has received funding from the European Union’s Horizon Europe Research and
Innovation Program under the Marie Skłodowska-Curie grant agreement No 101119442.

# FOLDERS
----------------------------------------------------------------------------
"md_traj/" folder contains the features extracted from the MD trajectories, 
"msm_pcca/" folder contains the predicted structures and associated features, 
"pdbs/" folder contains the crystallographic structures and associated features, 
"coupl/" folder contains the features and associated coupling values
# PYTHON SCRIPTS
fcp.ipynb is the jupyter-notebook for training the models, make predictions and reproduce the Figures in the paper
# TRAINED ML MODELS
"angles_rf_model.pkl" is the machine learning model to classify FCPs, "coupl/coupl_model.pkl" is the trained gradient boosting model to calculate excitonic couplings based on FCP protein conformation
Copyright
Prof. V. Daskalakis
Department of Chemical Engineering
University of Patras
vdaskalakis@upatras.gr
