# Chronic-Kidney-Disease
Analysis of potential risk factors for Chronic Kidney Disease (CKD)

Data Source: 
https://archive.ics.uci.edu/ml/datasets/Chronic_Kidney_Disease

Libraries version:
Python 3.9.13,
pandas 1.4.4,
numpy 1.21.5,
matplotlib 3.7.1,
seaborn 0.12.2,
xgboost  1.7.4,
scikit-learn 1.0.2,
jupyterlab 3.5.2

Goal of the analysis: 
Analysis of the Chronic_Kidney_Disease (CKD) Data Set (https://archive.ics.uci.edu/ml/datasets/Chronic_Kidney_Disease) to help a physician understand:
1. risk factors for CKD 
2. potential CKD subtypes

Features:
1.Age(numerical) age in years,
2.Blood Pressure(numerical) bp in mm/Hg,
3.Specific Gravity(nominal) sg - (1.005,1.010,1.015,1.020,1.025),
4.Albumin(nominal) al - (0,1,2,3,4,5),
5.Sugar(nominal) su - (0,1,2,3,4,5), 
6.Red Blood Cells(nominal) rbc - (normal,abnormal),
7.Pus Cell (nominal) pc - (normal,abnormal),
8.Pus Cell clumps(nominal) pcc - (present,notpresent),
9.Bacteria(nominal) ba - (present,notpresent),
10.Blood Glucose Random(numerical) bgr in mgs/dl,
11.Blood Urea(numerical) bu in mgs/dl, 
12.Serum Creatinine(numerical) sc in mgs/dl,
13.Sodium(numerical) sod in mEq/L,
14.Potassium(numerical) pot in mEq/L,
15.Hemoglobin(numerical) hemo in gms,
16.Packed Cell Volume(numerical)
17.White Blood Cell Count(numerical) wc in cells/cumm,
18.Red Blood Cell Count(numerical) rc in millions/cmm,
19.Hypertension(nominal) htn - (yes,no),
20.Diabetes Mellitus(nominal) dm - (yes,no),
21.Coronary Artery Disease(nominal) cad - (yes,no),
22.Appetite(nominal) appet - (good,poor),
23.Pedal Edema(nominal) pe - (yes,no),
24.Anemia(nominal) ane - (yes,no)

Target:
Classification (ckd, notckd)
