Below are the code required to generate data from CRUW dataset, run the code as well as do the inference. 



CRUW_Data_SR -  For CRUW-SR dataset generation using the trained DLSR model
CRUW_Segmentation, CRUW_Segmentation_for_obj_det - For generating the segmented CRUW dataset (CRUW-Seg dataset) - The files contain the codes to etract out the sgmented patch from CRUW dataset with 3 classes and 4 classes dataset respectively
CRUW_SR_accuracy_testing - For testing the accuracy of the predictions from DLSR model on CRUW dataset
CRUW_SR_preparation_for_obj_det - For carrying out the process of masking and segment extraction for the 2nd stage of object classification
CRUW_statistics - For generating the required statistics for the CRUW data
RADAR_hr-lr-Sim* - For simulating lr-hr pair of radar images (which are used for DLSR stagetraining) with different variations - like noises and shapes
RADAR_SR_* - DLSR model design and training (DLSR Stage implementation)



We have provided the pre-trained models to generate the CRUW-SR dataset. Pl. use the link to download the pre-trained model. 
https://drive.google.com/file/d/1hBOEB3vGZNhbVWPifubU-WuhRdFOVlb5/view?usp=sharing

These models were trained on the simulated LR-HR pair of datasets. The shared model is the final model that gave the best F1-score. The pre-trained weights for other variations like architecture variation, loss variation, noise variation, etc may be shared after a request to the author through email. The path to feed the model into the code is there in CRUW_Data_SR.ipynb. 






