# msc_thesis
Code for MSc Thesis DS (UvA)

The code is divided into 2 files. The EDA file (eda_final.ipynb) contains code for the plots we created during the EDA process. In addition, this file also contains the analysis we performed to obtain insights on different reporting behaviors within participants of the PEP study. 

Furthermore, the main python file (preds.ipynb) contains the code for the predictive modeling phase. In this file you will find the variations of all 3 models, namely the prediction of TR, prediction of symptom reports using multi-output-classification, and prediction of TUC. 

Both files contain the exact same process to load and pre-process the data. We start by merging two PEP datasets, both containing studyID's to ensure joining is performed correctly for each participant. One df contains all the symptom reports and reports of restricted activity, while the other df contains demographic data about participants. The resulting dataframe (pandas DF) is ready for analysis and modeling. 
