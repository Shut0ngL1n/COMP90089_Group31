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
- `TabNet Deep Learning.ipynb`: We utilize TabNet as an advanced modeling approach because it efficiently handles tabular data while capturing complex relationships and interactions between feature variables and target classes. Its attention-based mechanism allows for improved interpretability and performance on structured datasets.
- `Random forest and feature importances analysis.ipynb`: This file contain the random forest model and feature improtances analysis. The Random Forest ensemble learning method combines multiple decision trees, allowing it to effectively capture complex relationships and interactions among features. Additionally, we conduct a comprehensive feature importance analysis to identify which features contribute most significantly to the model's predictions. This analysis helps in understanding the underlying patterns in the data and can guide future feature selection and engineering efforts.
