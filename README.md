# Repository rationale
COVID-19 has caused more than 219 million infections worldwide and resulted in more than 4.55 million deaths. 
SARS-CoV-2 infection can range from asymptomatic carriers to acute respiratory failure due interstitial pneumonia,
which can be fatal in a considerable proportion of patients, up to 14% [1].
The ICU admission rate involves about 32% of all hospitalizations. With the potential of new waves of COVID-19 infections driven by more transmissible variants, ICU hospitalization numbers are expected to rise, leading to shortages of 
ICU beds and critical management equipment.
Stressful conditions and burnout in health care providers can reduce their clinical performance, and a lack of accurate judgment can lead to increased 
mortality rates (15, 16).
 Since the original epidemic in Wuhan (China),
several mortality risk factors have been identified:
genetic predisposing factors [4]; demographic factors, in particular older age and male sex [5]; the
presence of comorbidities, especially cardiovascular and metabolic [6]; several laboratory findings
– decreased lymphocyte count, increased lactic
dehydrogenase (LDH), ferritin, and interleukin-6
(IL-6) [7]; and imaging findings [8]. 
therefore clinical decisions are mainly
based on expert opinion and clinical judgment.
Artificial intelligence (AI) represents a novel tool
for analyzing big data in medicine, since it can provide the chance to assess frequently a large number of relevant variables, their temporal changes
and interactions among variables with respect to
the prognostic outcome. Furthermore, machine
learning algorithms, such as decision trees, random forests, support vector machines, neural networks, and deep learning, can identify 
hidden patterns in clinical data [14].










we propose a personalized machine-learning (ML) method for predicting 
mortality in COVID-19 patients based on routinely available laboratory and clinical data on the day of ICU admission.
we aimed to develop a prognostic score for in-hospital mortality in patients admitted for COVID-19
pneumonia based on machine learning. 















-------------------------------------------------------------------------------------------------------------------------------------
- Cardiovascular diseases (CVD), defined as a general term for conditions affecting the heart or blood vessels,  is one of the main causes of mortality and morbidity as well as healthcare costs. There is evidence that age, high blood pressure, smoking, dyslipidemia and diabetes are the main factors that improve risk of cardiovascular diseases.

- Global Burden of Cardiovascular Diseases  nearly doubled  from 1990 (with 271 million) to 2019 (with 532 million). Likewise, the number of deaths increased from 12.1 million in 1990 to 18.6 million in 2019. China, India, Russia, the United States and Indonesia have currently the highest number of deaths from CVD. Cardiovascular diseases were  estimated to cause about 32% of all deaths in Argentina in 2009. 

- Consistent, comparable, and systematic analysis of long-term trends and patterns in global CVD are essential to guide public policy and provide benchmarks for decision makers. Countries should invest in existing cost-effective public health programs and clinical interventions to target modifiable risks, promote healthy aging across the lifespan, and reduce disability and premature death due to CVD. The increase in healthcare costs entails a great burden, both for patients and for the general population. For example, CVD was estimated to cost the EU Euro 169 billion annually.

- Since CVD are multifactorial, to estimate the risk of apparently healthy people experiencing a vascular event, it is necessary to monitor and act upon several different risk factors at the same time.  Both the American Heart Association and Argentine Society of Cardiology recommend routinely evaluating cardiovascular risk factors and calculating the risk of CVD at 10 years (level of evidence IB), with the aim of identifying those people who should benefit most from preventive action.

# What is the source of the data?
The datasets were obtained from the following link: https://www.kaggle.com/drateendrajha/health-screening-data/metadata

# What files does this repository contain?
- data_raw → This folder contains the file Health_Screening_Data.csv with the raw data, which will be cleaned and transformed.
- documents → This folder contains 2 files: data_clean.csv and data_to_model.csv. This files will be used to work on the "Graphics.ipynb" and "Models.ipynb" notebooks respectively.
- scripts → This folder contains the 3 notebooks created, which should be opened in the following order: Clean.ipynb, Graphics.ipynb and Models.ipynbs
- src → this folder contains 2 files: Cleaning_functions.py and Cleaning_functions.ipynb. They contain the functions that will be applied to the "Clean.ipynb" notebook.

# References
- Zylbersztejn H, Giorgi M: “Evaluación global de los factores de riesgo cardiovascular. Cálculo del riesgo miembros.” Revista Argentina de Cardiología: Consenso de Prevención Cardiovascular. Vol 80; Supl 2; Año 2012.
- Arnett DK, Blumenthal RS, Albert MA, Buroker AB, Goldberger ZD, Hahn EJ et al: “2019 ACC/AHA guideline on the primary prevention of cardiovascular disease: a report of the American College of Cardiology/American Heart Association Task Force on Clinical Practice Guidelines.” 2019;140:e596–e646.
- Roth G, Mensah G,  Johnson C, Addolorato G, Ammirati E, Baddour L et al: ”Global Burden of Cardiovascular Diseases and Risk Factors, 1990–2019.” 2020 Dec 22;76(25):2982-3021.
