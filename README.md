# Cuff less Blood Pressure Prediction 

Prediction of Blood Pressure from ECG and PPG signals using regression methods. 

### Dataset:

Dataset :  [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/00340/)

This database consist of a cell array of matrices, each cell is one record part. 

In each matrix each row corresponds to one signal channel: 

1: PPG signal, FS=125Hz; photoplethysmograph from fingertip 

2: ABP signal, FS=125Hz; invasive arterial blood pressure (mmHg) 

3: ECG signal, FS=125Hz; electrocardiogram from channel II 

### Feature Extraction:

<code> seven_features.m </code> - Code to extract the first 7 features (WN,PIR,PTT,HR,IH,IL,Meu)

<code> ppg_features.m </code> - Code to extract the ppg features 


<code> PTT_final.m </code> - Code to extract the PTT ( least error )



[Project_Page](https://sites.google.com/view/cufflessbp/home)

## Using the DL Code:

Dependencies :

1. Python 3 
2. Pytorch


<code> git clone https://github.com/jeya-maria-jose/Cuff_less_BP_Prediction </code>

<code> cd Cuff_less_BP_Prediction/ </code>


