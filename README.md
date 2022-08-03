# Repository rationale
- COVID-19 has caused more than 219 million infections worldwide and resulted in more than 4.55 million deaths. Since the epidemic, several mortality risk factors have been identified: genetic predisposing factors; demographic factors (older age and male sex); presence of comorbidities (cardiac, metabolic); several laboratory findings (lymphocyte count, lactic dehydrogenase, ferritin); imaging findings.

- Clinical decisions are mainly based on expert opinion and clinical judgment. Stressful conditions and burnout in health care providers can reduce their clinical performance, and a lack of accurate judgment can lead to increased mortality rates.

- Machine Learning represents a novel tool for analyzing big data in medicine, including interactions among variables with respect to the prognostic outcome. 

# Xhat is the purpose of this repository?

# What is the source of the data?

# What files does this repository contain?
- data_raw → This folder contains the file Health_Screening_Data.csv with the raw data, which will be cleaned and transformed.
- documents → This folder contains 2 files: data_clean.csv and data_to_model.csv. This files will be used to work on the "Graphics.ipynb" and "Models.ipynb" notebooks respectively.
- scripts → This folder contains the 3 notebooks created, which should be opened in the following order: Clean.ipynb, Graphics.ipynb and Models.ipynbs
- src → this folder contains 2 files: Cleaning_functions.py and Cleaning_functions.ipynb. They contain the functions that will be applied to the "Clean.ipynb" notebook.

# References
- Laino ME, Generali E, Tommasini T, Angelotti G, Aghemo A, Desai A et al: "An individualized algorithm to predict mortality in
COVID-19 pneumonia: a machine learning based study." Arch Med Sci 3, May 2022.
- Jamshidi E, Asgary A, Tavakoli N, Zali A, Setareh S, Esmaily H et al: "Using Machine Learning to Predict Mortality for COVID-19 Patients on Day 0 in the ICU." Frontiers in Digital Health: Jan 2022, Vol 3, Article 681608


we propose a personalized machine-learning (ML) method for predicting 
mortality in COVID-19 patients based on routinely available laboratory and clinical data on the day of ICU admission.
we aimed to develop a prognostic score for in-hospital mortality in patients admitted for COVID-19
pneumonia based on machine learning.
