Important Codes to be put in github
CRUW_Data_SR -  For CRUW-SR dataset generation using the trained DLSR model
CRUW_Segmentation, CRUW_Segmentation_for_obj_det - For generating the segmented CRUW dataset (CRUW-Seg dataset) - The files contain the codes to etract out the sgmented patch from CRUW dataset with 3 classes and 4 classes dataset respectively
CRUW_SR_accuracy_testing - For testing the accuracy of the predictions from DLSR model on CRUW dataset
CRUW_SR_preparation_for_obj_det - For carrying out the process of masking and segment extraction for the 2nd stage of object classification
CRUW_statistics - For generating the required statistics for the CRUW data
RADAR_hr-lr-Sim* - For simulating lr-hr pair of radar images (which are used for DLSR stagetraining) with different variations - like noises and shapes
RADAR_SR_* - DLSR model design and training (DLSR Stage implementation)


Codes that are not needed
CRUW_Pascal_VOC_Preparation - Dataset preparation for training the SSD model in the pascalVOC format
CRUW_Yolo_format_preparation - Dataset preparation for training the SSD model in the YOLO format
Image Super Resolution - Transfer learning of radar SR from Image SR
Model_Maker_* - For the effecientnet object detection model
pascal_to_csv - To convert from pascalVOC to csv format
SR_through_thresholding - Lame way for creating RADAR-SR images by passing through a threshold
SSD_format_images - Pre-processing of images for feeding them into SSD model







