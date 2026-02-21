### CrimeCast — Forecasting Crime Categories

---

### Overview
**CrimeCast** is a predictive modeling project that uses incident-level crime data to forecast the **crime category** for each reported incident.

> **"Your goal is to use this data to predict the type of crime that occurred."**   
> **"The dataset consists of the following files: train.csv; test.csv; sample_submission.csv."** 

---

### Repository Structure
- **`data/`** — raw and processed datasets (`train.csv`, `test.csv`, `sample_submission.csv`)  
- **`notebooks/`** — exploratory data analysis and modeling notebooks  
- **`src/`** — data processing, feature engineering, model training, and inference scripts  
- **`models/`** — saved model artifacts and checkpoints  
- **`reports/`** — evaluation results, figures, and model cards  
- **`README.md`** — this file

---

### Dataset Summary
**Files**
- **`train.csv`** — training set including the target **crime_category**.  
- **`test.csv`** — test set without the target; used for final predictions.  
- **`sample_submission.csv`** — example submission in the required format.

**Key Columns**
- **Location**, **Cross_Street**, **Latitude**, **Longitude**  
- **Date_Reported**, **Date_Occurred**, **Time_Occurred**  
- **Area_ID**, **Area_Name**, **Reporting_District_no**  
- **Modus_Operandi**, **Victim_Age**, **Victim_Sex**, **Victim_Descent**  
- **Premise_Code**, **Premise_Description**  
- **Weapon_Used_Code**, **Weapon_Description**  
- **Status**, **Status_Description**  
- **Crime_Category** (target)

---
