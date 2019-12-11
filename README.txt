This file is meant to explain how to reporduce our work. To make things easier to digest, we have split our analysis accross many notebooks. We process the data throughout these notebooks and save them to a folder to be read by subsequent notebooks. Thus, it is important that the notebooks are ran in the correct order and that this processed data folder exists on your machine.

For convienicence, the notebooks are numbered in the order they are meant to be ran, however, to be explicit, this is the correct order to run the notebooks in:
1) 1_wellness_exploratory_and_factor_analysis
2) 2_rpe_exploratory_and_factor_analysis
3) 3_gps_exploratory_analysis
4) 4_performance_vs_training_load_and_wellnesss
5) 5_yesterdays_load_vs_performance_and_wellness
6) 6_pca_for_gps_and_rpe

The processed data folder is called: processed_data. This folder is created by the first notebook if it does not exists, however, it creates it in the current working python directory which is where subsequent notebooks expect it to be. Thus, when running the notebooks, ensure that python's current working directoty contains all our notebook files.

