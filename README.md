# 869-Jogan tsunami, DNN inverse model

This is a code for performing inverse analysis of tsunami deposits using deep-learning neural network. The forward model fittnuss produces datasets of the thickness distribution of tsunami deposits with random initial conditions, and DNN constructed with tensorflow and keras learns the relation between initial conditions and depositional features. Then, the trained DNN model works as the inverse model for ancient or modern tsunami deposits. See details in Mitra et al., (2020) and Naruse and Abe (2017).

Explanation of files Version 1.0:

Forward_model_for_DNN_jogan_5gs_Rw820_400grid.py: The forward model for deposition from 869 tsunami

jogan_paper_5gs_Final: A jupyter notebook for performing the inversion

start_param_random_5500_jogan_gs5_rw820_400grid.csv: Teacher data. Initial conditions used for production of training datasets.

eta_5500_g6_300grid_jogan_gs5_rw820_400grid.csv: Training and test data produced by the forward model. This file is too large to store in GitHub, so that it is only available from Zenodo repository.

jogan_gs5.csv: Dataset of 2011 Tohoku-oki tsunami measured at the Odaka region, Japan. Volume-per-unit-area of 6 grain-size classes were recorded.

config_g5_400grid_gs.ini: Configuration file of the forward model used for production of the training datasets and inversion.

Post_interp_calculation.xlsx: Detailed calculation of measured grain-size distribution of 869 Jogan tsunami from Sendai region, Japan.

Cite the code: 10.5281/zenodo.7981290
