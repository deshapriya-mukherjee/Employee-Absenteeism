# Employee-Absenteeism

## Problem Statement : XYZ is a courier company. As we appreciate that human capital plays an important role in collection, transportation and delivery. The company is passing through genuine issue of Absenteeism. The company has shared it dataset and requested to have an answer on the following areas:
##### How many losses every month can we project in 2011 if same trend of absenteeism continues?

Our task is to build a predictive model which will classify the quality what changes company should bring to reduce the number of absenteeism depending on multiple numerical and categorical historical observations. Given below is a sample of the data set that we are using to predict the absenteeism hour:
Sample Dataset: (Total 21 Variables and 740 Observations)


##### Attribute Information:
1. Individual identification (ID).
2. Reason for absence (ICD).
Absences attested by the International Code of Diseases (ICD) stratified into 21 categories (I to XXI) as follows:
I. Certain infectious and parasitic diseases.
II. Neoplasms.
III. Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism.
IV.Endocrine, nutritional and metabolic diseases.
V. Mental and behavioral disorders.
VI. Diseases of the nervous system. VII. Diseases of the eye and adnexa.
VIII. Diseases of the ear and mastoid process.
IX. Diseases of the circulatory system.
X. Diseases of the respiratory system.
XI. Diseases of the digestive system.
XII. Diseases of the skin and subcutaneous tissue.
XIII. Diseases of the musculoskeletal system and connective tissue.
XIV. Diseases of the genitourinary system.
XV. Pregnancy, childbirth and the puerperium.
XVI. Certain conditions originating in the perinatal period.
XVII. Congenital malformations, deformations and chromosomal abnormalities.
XVIII. Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified.
XIX. Injury, poisoning and certain other consequences of external
Causes.
XX. External causes of morbidity and mortality
XXI. Factors influencing health status and contact with health services.
5
And 7 categories without (CID) patient follow-up (22), medical consultation (23), blood donation (24), laboratory examination (25), unjustified absence (26), physiotherapy (27), dental consultation (28).
3. Month of absence.
4. Day of the week (Monday (2), Tuesday (3), Wednesday (4), Thursday (5), Friday (6)).
5.  Seasons (summer (1), autumn (2), winter (3), spring (4)).
6.  Transportation expense.
7.  Distance from Residence to Work (kilometers).
8.  Service time.
9.  Age.
10. Work load Average/day.
11. Hit target.
12. Disciplinary failure (yes=1; no=0).
13. Education (high school (1), graduate (2), postgraduate (3), master and doctor (4)).
14. Son (number of children).
15. Social drinker (yes=1; no=0).
16. Social smoker (yes=1; no=0).
17. Pet (number of pets).
18. Weight.
19. Height.
20. Body mass index.

This is the target variable which will predict the correct Absenteeism
21. Absenteeism time in hours.


