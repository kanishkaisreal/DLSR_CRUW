Below are the code required to generate data from CRUW dataset, run the code as well as do the inference. 



CRUW_Data_SR -  For CRUW-SR dataset generation using the trained DLSR model
CRUW_Segmentation, CRUW_Segmentation_for_obj_det - For generating the segmented CRUW dataset (CRUW-Seg dataset) - The files contain the codes to etract out the sgmented patch from CRUW dataset with 3 classes and 4 classes dataset respectively
CRUW_SR_accuracy_testing - For testing the accuracy of the predictions from DLSR model on CRUW dataset
CRUW_SR_preparation_for_obj_det - For carrying out the process of masking and segment extraction for the 2nd stage of object classification
CRUW_statistics - For generating the required statistics for the CRUW data
RADAR_hr-lr-Sim* - For simulating lr-hr pair of radar images (which are used for DLSR stagetraining) with different variations - like noises and shapes
RADAR_SR_* - DLSR model design and training (DLSR Stage implementation)





