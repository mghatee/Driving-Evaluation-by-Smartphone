# Driving-Evaluation-by-Smartphone
Data of Smartphone Sensors for Congestion, Car Type, Maneuver Style, and Driving Style Classification

The data presented in this dataset are related to the research article entitled 
Bejani, M. M., & Ghatee, M. (2018). A context aware system for driving style evaluation by an ensemble learning on smartphone sensors data. Transportation Research Part C: Emerging Technologies, 89, 303-320.
Please refer to this paper for each usage.

This package includes five different datasets, which here is a guide for how to run them on Matlab and Weka.

 1-Smartphone-Calibration
This folder consists of four code-files (*.m) and a data-file (*.xlsx). For execution, main.m file should be opened in Matlab R2016a and run it. Index variable could be changed (as default is 330) for testing in new point. 
 
 2-Car-Classification
This folder consists of seven code-files (*.m), two matlab-data-file (*.mat), and there are raw data files (*.xlsx) in raw-data folder that is used for learning process. The class label of data given in each file is mentioned in its name, i.e., two class labels are soft (LSC) and hard (HSC). For execution, “main.m” file should be opened in Matlab R2016a and run it. 
 
 3-Initial-Style-Classification
This folder consists of six code-files (*.m), a data-file (*.mat), and there are raw data files (*.xlsx) in raw-data folder that is used for learning process. The class of each file is mentioned in its name. These labels are bad (dangerous driving) and good (normal driving). For execution, “ensembleLearningCrossValTest.m” file should be executed in Matlab R2016a. For extracting features from raw file, open main.m in Matlab R2016a and edit line 4 (as input file) and 42 (as output file). 
 
 4-Traffic-Classification
This folder consists of four code-files (*.m), five data-files (*.mat), and there are raw data files (*.xlsx)  in raw-data folder that is used for learning process. The class label of each file is mentioned in its name including idle (Normal Traffic Condition) and traffic (Congested Traffic Condition). For execution, “crossValTest.m” file should be opened in Matlab R2016a and run it. For changing dataset, edit line 3 (edit data-set name such as data-5.mat, data-10.mat, data-15.mat, data-20.mat, data-25.mat, data-30.mat, or data-40.mat). For extracting features from raw file, open main.m in Matlab R2016a and edit lines 3 (as input file) and 26 (as output file). For changing window length, edit the value of “windowLen” variable (default value is 50).
 
 5-Maneuver-Classification 
This folder has three code-files (*.m), a data-file (*.arff), and there are raw data files (*.xlsx) in raw-data folder that is used for learning process. The learning process is done by Weka. 

Experimental Design, Materials and Methods
The datasets were collected by a smartphone. Two experts labeled the recorded data. The datasets were collected by AndroSensor application.

