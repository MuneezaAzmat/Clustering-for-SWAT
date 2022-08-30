Run Generate HRU data before running this

## 01_Gen_Clustering_Data
#### Prerequisites:
run `Data_input_hru.ipynb` and have numpy arrays of numeric hru features data stored at location `data_path`
#### Reads: 
Region 02 data read from .hru output files and saved into numpy arrays. 
#### Parameters: 
`Clustering_feature_names` : Change the features used for clustering. 
#### Saves:  
Saves monthly average over 38 years of the simulation (months, hrus, features) for each HRU. The output file is subbasin level 'subbasinid.num_hrus'

## 02_Elbow_test

## 03_Clustering

## 04_Gen_SMest_Data

## 05_SingleStep_TGCN

## 07_MultiStep_TCN
