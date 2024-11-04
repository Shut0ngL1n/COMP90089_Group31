# COMP90089_Group31

### Group 31
1. Louis Copland
2. Nicholas Larter
3. Shutong Lin
4. Hanbin Zhou

- `generic_features_for_positive_patient.csv`: This file contains de-identified generic features for HIV-positive patients, which we utilize as our true labels for modeling.
- `generic_features_for_random_patient.csv`: This file contains de-identified generic features for HIV-negative patients, randomly selected from the broader population. We utilize this dataset as our false labels for modeling, providing a crucial counterpoint to our true labels derived from HIV-positive individuals.
  
- `sql&preprocessing.ipynb`: Using SQL queries to extracted generic features data from the MIMIN-IV database via Google BigQuery. We also include the data preprocessing step in this file. This included filtering out redundant or irrelevant information that could potentially interfere with our results and addressed missing data (NaN values) by employing appropriate imputation methods. 
- `Logistic Regression.ipynb`: We use logistic regression as our baseline model because it effectively captures the linear relationship between the generic feature variables and the target classes.
- `TabNet Deep Learning.ipynb`:
