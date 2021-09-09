# Analysis-of-MIMICS-database-
Neural network and machine learning algorithms for re-hospitalizations regression and classification. 

With the part of the MIMICS dataset available I propose two best  supervised models to 
predict : 
- the number of days to next re-hospitalization (assessment metrics, MSE on predicted 
number of days) (regression) 
- re-hospitalization (evaluation metrics, accuracy) (classification)

For both approaches I develop two models using or not the discharge medical report (TEXT)

Available features: 
- DOB: Date of Birth 
- GENDER 
- MARITAL_STATUS 
- ETHNICITY 
- INSURANCE 
- DEATHTIME: Date of Death (if the patient has died) 
- ADMITTIME: date of the admission 
- ADMISSION_TYPE  
- blood', 'circulatory', 'congenital', 'digestive', 'endocrine', 'genitourinary', 'infectious', 
'injury',  'mental',  'misc',  'muscular',  'neoplasms',  'nervous',  'pregnancy',  'prenatal', 
'respiratory', 'skin']: bag of word representation of DIAGNOSIS 
- DISCHTIME: date of the discharge 
- DISCHARGE_LOCATION: patient's destination after discharge from hospital 
-TEXT (discharge medical report) 
 
Others variables used or in the pre-process strategy or as target are showed below:  
- DAYS_NEXT_ADMIT: number of day beetween discharge and readmission 
- NEXT_ADMITTIME: date of the readmission 
- OUTPUT_LABEL: 
- DEATHTIME: Date of Death (if the patient has died) 
 

The results are presented with two ipynb files: 
- DL-4.ipynb for the regression tasks 
- ML final-Copy1.ipynb for the classification tasks
