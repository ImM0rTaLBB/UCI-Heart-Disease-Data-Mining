# UCI Heart Disease Feature Engineering and Model Evaluations
 
## Dataset Columns:
* id (Unique id for each patient)
* age (Age of the patient in years)
* origin (place of study)
* sex (Male/Female)
* cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
* trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
* chol (serum cholesterol in mg/dl)
* fbs (if fasting blood sugar > 120 mg/dl)
* restecg (resting electrocardiographic results)
* Values: [normal, stt abnormality, lv hypertrophy]
* thalch: maximum heart rate achieved
* exang: exercise-induced angina (True/ False)
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by fluoroscopy
* thal: [normal; fixed defect; reversible defect]
* num: the predicted attribute

## Data Structure:
* sex: There are 194 females and 726 males in the dataset.
* dataset: The data comes from multiple sources with the following counts - Cleveland: 304, Hungary: 293, Switzerland: 123, VA Long Beach: 200.
* cp (Chest Pain Type): There are four types of chest pain recorded in the dataset with the following counts - asymptomatic: 496, atypical angina: 174, non-anginal: 204, typical angina: 46.
* fbs (Fasting Blood Sugar): 138 individuals have fasting blood sugar greater than 120 mg/dl (True), and 692 do not (False).
* restecg (Resting Electrocardiographic Results): The results are distributed as - normal: 551, LV hypertrophy: 188, ST-T abnormality: 179.
* exang (Exercise-Induced Angina): 337 individuals experience exercise-induced angina (True), while 528 do not (False).
* slope (Slope of the Peak Exercise ST Segment): The slopes are recorded as - flat: 345, upsloping: 203, downsloping: 63.
* thal (Thalium Stress Test Result): The results are distributed as - reversable defect: 192, fixed defect: 46, normal: 196.

## Data Types:
* id: int64
* age: int64
* sex: object (string)
* dataset: object (string)
* cp: object (string)
* trestbps: float64
* chol: float64
* fbs: object (string, likely boolean)
* restecg: object (string)
* thalch: float64
* exang: object (string, likely boolean)
* oldpeak: float64
* slope: object (string)
* ca: float64
* thal: object (string)
* num: int64

## Missing Data:
* id: 0 missing
* age: 0 missing
* sex: 0 missing
* dataset: 0 missing
* cp (chest pain type): 0 missing
* trestbps (resting blood pressure): 59 missing
* chol (serum cholesterol): 30 missing
* fbs (fasting blood sugar): 90 missing
* restecg (resting electrocardiographic results): 2 missing
* thalch (maximum heart rate achieved): 55 missing
* exang (exercise-induced angina): 55 missing
* oldpeak: 62 missing
* slope (slope of the peak exercise ST segment): 309 missing
* ca (number of major vessels colored by fluoroscopy): 611 missing
* thal: 486 missing
* num: 0 missing
