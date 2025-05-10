This respository has been created to satisfy the requirements of MIS581 Capstone class for CSU-Globals MS in Data Analytics
****
Data used for the analysis has been uploaded:
Capstone_Predictors_N_1182.xlsx is the full data set used. 
Capstone_Predictors_N_1182_AlkG61.xlsx is the data set that was created that has all of the ALK_RAW variables that are > 61. 
Capstone_Predictors_N_1182_AlkL61.xlsx is the data set that was created that has all of the ALK_RAW variables that are < 61.
****
MIS581_Capstone_Portfolio_Tables.xlsx is a workbook that was used to create tables for the paper from SAS ODA outputs.  The file contains screenshots from SAS ODA.  
  Please note that there are multiple tabs in the work book that correspond to sections in the paper. 
****
Code generated in SAS ODA has been uploaded: 
SAS_Sumamry_Stats_01 has the descriptive stats for variables of interest. 
SAS_Sumamry_Stats_01 has the descriptive stats for variables of non-interest. 
****
Series Plots in SAS ODA: 
RawQ
Raw_ALK
Raw_TOC
TOCRemPerc
****
Correlation Analsys
CORR_Analysis_01 = variables of interest
CORR_Analysis_02 = variables of non-interest
****
Exploratory Regression
ExpReg ALL = regression using all predictors (based on all variables in RAW_ALK)
ExpReg AlkG61 = regression using RAW_ALK predictors > 61
ExpReg AlkL61 = regression using RAW_ALK predictors < 61
****
ExpReg ALL StepWise = regression using all predictors (based on all variables in RAW_ALK) using SAS StepWise feature selection
ExpReg AlkG61 StewpWise = regression using RAW_ALK predictors > 61 using SAS StepWise feature selection
ExpReg AlkL61 StewpWise = regression using RAW_ALK predictors < 61 using SAS StepWise feature selection
****
Predicitve modeling using 70:15:15 (Train:Validate:Test) data partitions via SAS ODA predicitve regression model task (Random seed = 1234)
PredReg AlkG61 LASSSO 01
PredReg AlkL61 LASSSO 01
Predicitive Score Code output from SAS for PredReg AlkG61 LASSSO 01
Predicitive Score Code output from SAS for PredReg Alkl61 LASSSO 01

