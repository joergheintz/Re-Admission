## Introduction: Predicting All Cause 30-day Readmission Risk in Heart Failure Index Admissions

The Patient Protection and Affordable Care Act (ACA) of 2010 penalizes health systems with higher than expected readmission rates and creates a strong incentive for hospital systems to identify, at the time of discharge, those patients who are at high risk of being readmitted. 

Readmission rates, defined by the Centers for Medicare and Medicaid Services (CMS), are a risk-standardized rate of unplanned all-cause readmission after admission for any condition within 30 days of hospital discharge. The indicator is a single summary score that comprises risk-standardized rates of different hospital cohorts e.g. general medicine, surgery/gynecology, cardiorespiratory, cardiovascular, neurology, oncology, and psychiatry. The indicator is calculated by 1-year data and influences reimbursement decisions. 


## Project Scope and Data Set 

This project aims to predict the readmission within 30 days of patients at the moment of discharge. You are provided a labeled data set with the following characteristics. 
*. Sample Size: 4320  
*. Number of readmission case : 777  
*. The ratio of readmission case is 17.9%, and thus the dataset is imbalanced  
*. Number of features: 832
*. Binary (Nominal) Variable: 501
*. Ordinal Variable: 2
*. Interval Variable: 329

### Approach
- Data Cleaning
- Feature Selection
- Model Selection
- Training Model (k-fold)
- Validating / Testing the Model


### Classification Models
- Logistic Regression
- Random Forrest
- Support Vector Machine
- other you can choose 

### Data

- [Sample Data Set](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/SampleData.csv)
- [Data Set](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/OSF_Readmission_Data.csv)
- [Data Dictionary](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/HF Readmission Intern Project Data Dictionary.xlsx)

### Features to begin with:
- **CMSReadmit [Label]**
- IPCount180, 
- MedsVisitBetaBlockers,
- HCC_CongestiveHeartFailure,
- MedsVisitAnalgesicsNonnarcotic,
- EDCount90,
- BmiClassSpecific,
- Meds12mo_MedicalDevicesRAW, 
- IPCount60,
- PastIP2IPReadmitRate,
- HCC_DialysisStatus,
- Meds12mo_AntidotesRAW,
- Meds12mo_AntihyperlipidemicRAW, 
- PCP_Listed,
- HCC_CoagulationDefects,
- Meds12mo_VitaminsRAW, 
- Meds12mo_CardiovascularRAW,
- LOS,
- MedsVisitAntianginalAgentsRAW,
- Obs2Obs180, 
- PastIP,
- Meds12mo_AntihypertensiveRAW, 
- OPCount180, 
- HCC_AcuteRenalFailure,
- IPCount365

