## Introduction: Predicting All Cause 30-day Readmission Risk in Heart Failure Index Admissions

The Patient Protection and Affordable Care Act (ACA) of 2010 penalizes health systems with higher than expected readmission rates and creates a strong incentive for hospital systems to identify, at the time of discharge, those patients who are at high risk of being readmitted. 

Readmission rates, defined by the Centers for Medicare and Medicaid Services (CMS), are a risk-standardized rate of unplanned all-cause readmission after admission for any condition within 30 days of hospital discharge. The indicator is a single summary score that comprises risk-standardized rates of different hospital cohorts e.g. general medicine, surgery/gynecology, cardiorespiratory, cardiovascular, neurology, oncology, and psychiatry. The indicator is calculated by 1-year data and influences reimbursement decisions. 

## Project Scope and Data Set 
This project aims to predict the readmission within 30 days of patients at the moment of discharge. You are provided a labeled data set and your prediction accuracy should be above 0.60. The data set is provided is imbalanced and consists of 4320 records of which 777 are readmitted cases. We are provided with 832 features, whereby 501 are binary, 2 ordinal and 329 are interval variables. You are free in choosing your classification models. You should try Logistic Regression, Random Forrest, aSupport Vector Machine, and one other if you wish. 

### Approach
We recommend you to start with scanning the sample data set, and then start wtih data cleaning, feature selection (see recommendation below), select your models,  create your test and training data set (5 k-fold is recommended) and start training and testing your models. 

### Data
- [Sample Data Set](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/SampleData.csv)
- [Data Set](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/OSF_Readmission_Data.csv)
- [Data Dictionary](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/Dictionary.xlsx)

### Features to begin with:
- **CMSReadmit [Label]**
- IPCount180
- MedsVisitBetaBlockers
- HCC_CongestiveHeartFailure
- MedsVisitAnalgesicsNonnarcotic
- EDCount90
- BmiClassSpecific
- Meds12mo_MedicalDevicesRAW
- IPCount60
- PastIP2IPReadmitRate
- HCC_DialysisStatus
- Meds12mo_AntidotesRAW
- Meds12mo_AntihyperlipidemicRAW
- PCP_Listed
- HCC_CoagulationDefects
- Meds12mo_VitaminsRAW
- Meds12mo_CardiovascularRAW
- LOS
- MedsVisitAntianginalAgentsRAW,
- Obs2Obs180
- PastIP
- Meds12mo_AntihypertensiveRAW
- OPCount180 
- HCC_AcuteRenalFailure
- IPCount365
