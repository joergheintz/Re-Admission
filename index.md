## Introduction: Predicting All Cause 30-day Readmission Risk in Heart Failure Index Admissions

The Patient Protection and Affordable Care Act (ACA) of 2010 penalizes health systems with higher than expected readmission rates and creates a strong incentive for hospital systems to identify, at the time of discharge, those patients who are at high risk of being readmitted. 

Readmission rates, defined by the Centers for Medicare and Medicaid Services (CMS), are a risk-standardized rate of unplanned all-cause readmission after admission for any condition within 30 days of hospital discharge. The indicator is a single summary score that comprises risk-standardized rates of different hospital cohorts e.g. general medicine, surgery/gynecology, cardiorespiratory, cardiovascular, neurology, oncology, and psychiatry. The indicator is calculated by 1-year data and influences reimbursement decisions. 


## Project Scope

This project aims to improve upon OSF Healthcare’s current Readmission Risk Model in a meaningful and functionally significant manner by focusing effort on disease specific subsets of the data.  The current production system uses a combination of four sub-models to predict admitted inpa-tient risk of a CMS defined 30-day all-cause readmission.  Training occurred on the general inpa-tient population.  This project focuses on the Heart Failure subset of inpatient admissions with an end goal of creating a Heart Failure specific readmission model that is both an improvement to the current model’s performance on the Heart Failure sub-population and is deployable within our existing production infrastructure.

```markdown
# Models
- Logistic Regression
- Random Forrest
- Support Vector Machine

# Approach
- Data Cleaning
- Feature Selection
- Model Selection
- Training Model
- Validating / Testing the Model

# Download Data
- Data Set
- Data Dictionary
- ...

```

[link](https://github.com/joergheintz/Hospital-ReAdmission-Data/blob/gh-pages/SampleData.csv)

Features to begin with:
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

