# Model to help doctors to determine whether changing their patients medication will either help or deter their health.
by: Edward Kerr
## Abstract
People with diabetes have to live on medication for the rest of their lives. Doctors have a lot to factor in before chaning their medications. Many patients have to take multiple medications to regulate their bodily functions.  
## Design
The goal of this project was to use classification to help build models that can assist doctors on whether increasing, decreasing or not change dosages for their diabetic patients. The data was gathered from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008#). Python was the main tool used for analysis. Used seaborn for creating plots and classification metrics to create a model.
## Data
The data was downloaded from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008#). This data set has 100,000 number of instances with 55 features or attributes. The feature consist of patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc. This dataset will be used to build a predictive model to help doctors diagnose patients in a more efficient way. 
## Algorithms
Used Python to perform EDA. Used seaborn to create pairplots to analyze the features of the data set. Then applied logistic regression and random forest to determine the best features to used to build a classification model. The accuracy score of the random forest was used to for feature analsis while for logistic regression, the score, coeffiecent, and intercept were used.
## Tools
- Python
- Libraries in Python: seaborn, sklearn, pandas, and numpy
